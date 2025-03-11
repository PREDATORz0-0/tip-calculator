# Tip Calculator

Tip calculator pseudocode

```
BEGIN
    DISPLAY user for the original bill amount (before tip)
    IF bill amount is not a positive number
        PRINT "Invalid input. The bill amount should be a positive number."
        EXIT    
    DISPLAY user for the quality of service (poor, fair, good, excellent)
    IF service quality is not one of the valid options (poor, fair, good, excellent)
        PRINT "Invalid input. Please enter a valid service quality."
        EXIT
    DISPLAY user for the number of people splitting the bill
    IF number of people is not a positive integer
        PRINT "Invalid input. The number of people should be a positive integer."
        EXIT
    IF service quality is "poor"
        SET tip percentage to 10%
    ELSE IF service quality is "fair"
        SET tip percentage to 15%
    ELSE IF service quality is "good"
        SET tip percentage to 18%
    ELSE IF service quality is "excellent"
        SET tip percentage to 20%
    END IF
    CALCULATE the tip amount: tip amount = bill amount * tip percentage / 100
    CALCULATE the total amount: total amount = bill amount + tip amount
    CALCULATE the amount each person should pay: amount per person = total amount / number of people
    PRINT the original bill amount
    PRINT the service quality and corresponding tip percentage
    PRINT the calculated tip amount
    PRINT the total amount including tip
    PRINT the number of people splitting the bill
    PRINT the amount each person should pay
END


```
