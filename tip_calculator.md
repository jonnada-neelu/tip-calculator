# Tip calculator generator
```
START
INPUT bill_amount, service_quality, num_people
PRINT " Enter  bill amount:", bill_amount
 IF bill_amount<=0 then
  PRINT "  Bill amount is invalid"
 EXIT
PRINT " Enter service quality(poor, fair, good, execellent): ", service_quality
  IF service_quality = "poor" then
    tip_percentage = 0.10
ELSE IF service_quality = "fair" then
    tip_percentage = 0.15
ELSE IF service_quality = "good" then
    tip_percentage = 0.18
ELSE IF service_quality ="execellent" then
    tip_percentage = 0.20
ELSE
  PRINT "Error: Invalid service quality"
EXIT
PRINT " Enter number of people:", num_people
IF num_people<=0 then
 PRINT " Invalid number"
EXIT
tip_money =  bill_amount*tip_percentage
total_amount = bill_amount + tip_money
amount_perpserson = total_amount/num_people

PRINT " Bill Amount: $" +bill_amount
PRINT " Service Quality :" +service_quality + "("+ tip_percentage*100 + "%)"
PRINT " Tip Amount : $" +tip_money
PRINT "Total Amount: $" +ttotal_amount
PRINT "Number of people : " +num_people
PRINT "Amount per person :" +amount_perperson
 
END
```
