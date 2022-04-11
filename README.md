# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![](https://github.com/mquimi/MechaCar_Statistical_Analysis/blob/main/imgs/Linerar_Regression.png)
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
<br>The two variables that provided a non-random amount of variance to the mpg values were the vehicle length and the groun_clearance. 
<br>
- Is the slope of the linear model considered to be zero? Why or why not?
<br>From the screenshot above, both variables have a small p-value, which means that we have sufficient evidence to say that there was a siginificant impact on the mpg value. The linear regression shows that some variables had an effect on the dependant variable making the slop not zero.
<br>
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
<br>The r-squared value of the multiple linear regression model is the main reason of why the linear regression model predicts the mpg of the MechaCar: 0.71. In conclusion, this model would be considered effective.

## Summary Statistics on Suspension Coils

Total Summary Table:
![](https://github.com/mquimi/MechaCar_Statistical_Analysis/blob/main/imgs/total_summary.png)

Lot Summary Table:
![](https://github.com/mquimi/MechaCar_Statistical_Analysis/blob/main/imgs/lot_summary.png)
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Based on the two data sets that were created and the limitation of not exceeding 100 pounds per sq in the variance, the Total Summary Table shows that the overall variance is under 100 pounds per sq. For the Lot Summary Table the variance for lot 3 has variance over 100, 170.30.

## T-Tests on Suspension Coils

![](https://github.com/mquimi/MechaCar_Statistical_Analysis/blob/main/imgs/one_sample_T_test.png)

![](https://github.com/mquimi/MechaCar_Statistical_Analysis/blob/main/imgs/Lots.png)

- The p-value is .6028. If we assume that our significance level was the common .05%, then the p-value is more than our significane level, meaning we do not have suffiencinet evidence to reject the null hypothesis and the two means are similar.

## Study Design: MechaCar vs Competition

- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?

When comparing MechaCar to its competition, the MechaCar should consider using an ANOVA test to compare the MechaCar in various categories such as:

                - cost
                - city 
                - highway fuel efficiency
                - horse power, safety rating
                - maintenance cost

The ANOVA test will test to see if the means from different samples are  similar or different. If the p-value is > than 0.05%, then MecahCar has the same or similar performance within these categories (the null hypothesis). If the p-value is < than 0.05%, then MechaCar is significantly different. If MechaCar's average is below or above, the other averages would show how it's performing against its competitors (below = worse, above = better)