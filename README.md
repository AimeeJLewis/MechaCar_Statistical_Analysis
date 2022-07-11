# MechaCar_Statistical_Analysis
## Overview
## Linear Regression to Predict MPG
![Deliverable 1 Lin Reg](https://user-images.githubusercontent.com/101950175/176278288-05b8f8d7-94a3-4e94-bc75-6e11d92ceddb.png)
![Deliverable 1 Summary Lin Reg](https://user-images.githubusercontent.com/101950175/176278298-750cbd08-caf3-4cb1-8e9c-8e6976d4ee51.png)
### Statstical Analysis
**1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**
<br>
The vehicle length and ground clearance are statitstially likely to provide non-random amounts of variance to the mpg value due to the fact that they both have a p-value with a significance level less than 0.05.
<br>
**2. Is the slope of the linear model considered to be zero?  Why or why not?**
<br>
Since we have a p-value of 5.35e-11 and we are taking our assumed significance level of 0.05%, we can state that there is sufficient evidence to reject the null hypothesis and that the slope of our linear model is zero.
<br>
**3. Does this linear model predict mpg of MechaCar prototypes effectively?  Why or why not?**
<br>
Since R-squared is .7149, that means that roughly 71% have a strong positive correlation between the variables.  We could say that this linear model predict mpg of MechaCar prototypes effectively. 



## Summary Statistics on Suspension Coils
![Deliverable 2 Total Summary](https://user-images.githubusercontent.com/101950175/176287618-822a5d6d-fe3d-4158-8437-a8967b51ca21.png)
![Deliverable 2 Lot Summary](https://user-images.githubusercontent.com/101950175/176287320-fccdb6d0-7f5f-42e9-927a-d68e58b3951b.png)
### Statistical Analysis
**1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**
<br>
When looking at the variance for the total manufacturing lots, we find that the variance is 62.3 which is well below te manufacturers 100lbs per square inch specification.  However if you look at lots individually, we find that Lot3 has a variance of 170.3 which does NOT meet the specifications for the suspension coils.


## T-Tests on Suspension Coils
Assuming a significance level of 0.05 for all of the below T-Tests.
T-test for All Lots:
![Deliverable 3 total test](https://user-images.githubusercontent.com/101950175/176293500-48fbcc3a-9500-41b4-bba4-d68dd581bcb3.png)
p-value = 1, PSI not statistically significant.
<br>
T-test for Lot 1:
![Deliverable 3 test 1](https://user-images.githubusercontent.com/101950175/176293586-f1292383-e55c-4ea2-b38c-89e5140a5ad1.png)
p-value = 1.568e-11, PSI statistically significant.
<br>
T-test for Lot 2:
![Deliverable 3 test 2](https://user-images.githubusercontent.com/101950175/176293643-16aeea43-2839-4383-aee2-64b0e59f537c.png)
p-value = 0.0005911, PSI statistcally significant.
<br>
T-test for Lot 3:
![Deliverable 3 test 3](https://user-images.githubusercontent.com/101950175/176293700-664d657a-42df-42cd-bc73-38ef70a292e9.png)
p-value = 0.1589, PSI not statistically significant.
<br>


## Study Design: MechaCar vs Competition
<br>

**Q. What metric or metrics are you going to test?**

<br>

The next metric that could be tested could be highway fuel efficiency in different makes of cars/trucks.  As a consumer, I always look at fuel efficiency whether it is highway or city.
<br>
**Q. What is the null hypothesis or alternative hypothesis?**
<br>
The null hypothesis would be the highway fuel efficiency is statistically different between V6 engines and V8 engines.  The alternative hypothesis would be the highway fuel efficiency is not statistically different between v6 engines and v8 engines. 
<br>
**Q. What statistical test would you use to test the hypothesis? And why?**
<br>
A multiple linear regression would be used to determine the fuel efficiency of each engine and the variables that would impact it's efficiency compared to other competitors.
<br>
**Q. What data is needed to run the statistical test?**
<br>
A random sample of highway fuel efficiency data would need to be collected from V6 engines and V8 engines over a set time period. 
