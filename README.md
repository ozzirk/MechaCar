# MechaCar
## Linear Regression to Predict MPG

-   Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
	- Vehicle length and ground length
-   Is the slope of the linear model considered to be zero? Why or why not?
	- No, the r-squared value was .71
-   Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
	- Yes, the results are statistically significant

![enter image description here](https://github.com/ozzirk/MechaCar_Statistical_Analysis/blob/main/Linear.jpg?raw=true)

## Summary Statistics on Suspension Coils

-   The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
	- Lots 1 & 2 conform with this specification, however, Lot 3 does not as the variance is far greater than 100

![enter image description here](https://github.com/ozzirk/MechaCar_Statistical_Analysis/blob/main/lot_sum.png?raw=true)
![enter image description here](https://github.com/ozzirk/MechaCar_Statistical_Analysis/blob/main/total_sum.png?raw=true)



## T-Tests on Suspension Coils
Lots 1 and 2 don't produce a statistically significant number to reject the null hypothesis. Lot 3, does, however, and we are able to reject the null hypothesis. 

![enter image description here](https://github.com/ozzirk/MechaCar_Statistical_Analysis/blob/main/ttest.png?raw=true)


## Study Design: MechaCar vs Competition


In closing, we can evaluate how the MechaCar performs against the competition by testing metrics that are important to the modern consumer. We would look at fuel efficiency, cost, and safety ratings. A null hypothesis would surmise that there is no discernable difference between the MechaCar and competitor's vehicles, while an alternative hypothesis would conclude that MechaCars are truly superior in those categories. In order to test empirically, we would need to run a series of tests that would most likely include linear regression, t.tests, and cost comparisons. These tests would give a full picture of the metrics that we are seeking to prove. We would require proprietary data from both MechaCar and competitors in order to successfully complete the necessary testing.
