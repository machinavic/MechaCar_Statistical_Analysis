# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Linear_Regression](D:\LACHY\BUSINESS ANALYTICS BOOTCAMP_UM\MODULE 16\MechaCar_Statistical_Analysis/Linear_Regression.png)

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**
On this deliverable, the Multiple Linear Regression model was carried out defining as dependent variable the MPG, and as independent variables the remaining ones such as: vehicle length, vehicle weight, spoiler angle, ground clearance and AWD.

Taking a significance level of 5%, and comparing the p-value obtained from this model, it could say that all the independent variables provided a non-random amount of variance in the dataset. This could be demonstrated as well with the R-Squared which it was about 71.5% explanation of the variance in this dataset.

**Is the slope of the linear model considered to be zero? Why or why not?**
Despite all of the coefficients related to this model are near zero, the linear model for this study can't be considered like that because in a multiple linear regression model, the slope represents the change in the response variable (y) for a one-unit increase in the predictor variable (x), holding all other predictor variables constant. The slope is not considered to be zero unless the corresponding coefficient for the predictor variable is zero which is not the case here. Besides, the p-value is less than 0.05 as it was explained in the previous paragraph.indicating that the predictor variable has a non-zero effect on the response variable, and therefore, the slope is not considered to be zero.

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**
In the first paragraph the R-square value was taken into account to explain on how well the model characterize this dataset, so again to predict if the "mpg" predicts very well the results from this model, the answer is "yes" because the R-square is explainining around the 72% variability of this model.

## Summary Statistics on Suspension Coils
## T-Tests on Suspension Coils

![T_test](D:\LACHY\BUSINESS ANALYTICS BOOTCAMP_UM\MODULE 16\MechaCar_Statistical_Analysis/T_test.png)

**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

Addressing this question related to the Suspension Coil analysis done in the software, it can be said the current manufacturing data does not meet the design specification for all manufacturing lots in total neither individually for all the lots included in this study.

Example of this is the first result gotten when the t-test was made for the entire population where the p-value was above the significance level @ 6%. This denotes that was not almost any statistical difference between the samples and the population mean in this test.  Same occured when subset for the lot 1 and 2 were compared as well. They were above the significance level as well.
The only lot was lot3 and not so convincent cause the general variance was the highest in the sample.

## Study Design: MechaCar vs Competition

Designing statistics study for this topic in a way to quantify the MechaCar'sperformance compared with the competition, we can include whatever metrics we are interested in to study, but is not actually what metrics are included, but if these metrics are representative for the experiment or not.

In this case, we can proceed firstly to do a correlation analysis between all of the variables/metrics included here, and then carry out a multiple regression model to predict some results taking the most important variable as a target vs. all others.

Null hypothesis or alternative hypothesis? Example:
Ho: MPG has no effect on the efficiency of the car's performace.
H1: MPG has effect on the efficiency of the car's performace.

What statistical test would you use to test the hypothesis? And why?
If the success metric is numerical and the sample size is small, I would use a z-score summary statistic.

What data is needed to run the statistical test? As much as we be able to collect in orer the sample be significant.

