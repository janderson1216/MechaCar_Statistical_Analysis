# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  1. Vehicle Length 
  2. Ground Clearance
  
2. Is the slope of the linear model considered to be zero? Why or why not?

  No because of the variable have different numbers, therefore it is not a flat line. 

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  The p-value is much lower than .05 and the multiple R-Squared is .7, therefore we can determine that future data points are likely to follow the linear model.
  
  ![Del_2](Resources/Del_2.png)

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  Currently the manufactoring lots in total meet this design specification with a mean variance of 62.3. However, Manufactoring Lot 3 has a mean variance in PSI's of 170.2. 
  
## T-Tests on Suspension Coils

The data above determines if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch. Lots 1 and 2 have p-valoues greater than .05, meaning there is no statistical difference. Lot 3 has a a p-value of .04 which means there is a difference between lot 3 and the population mean. This is confirmed by the mean of x being listed at 1496.14. 

![Lot_1](Resources/Lot_1.png)
![Lot_2](Resources/Lot_2.png)
![Lot_3](Resources/Lot_3.png)


## Study Design: MechaCar vs Competition
The study will look at the initial cost and maintainance cost of MechaCar vs its competitors. The study will first us linear regression see if there is a relationship between initial cost of the vehicle and the maintance cost. The null hypothesis is vehicle cost does not impact maintainance cost. If the study finds you are able to predict maintainance cost based on initial car cost, we will compare MechaCar's linear model with its competitors. 
