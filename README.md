# Multiple Linear Regression Predicting Cholesterol
For the full presentation please read: https://github.com/benlaird/health-project/blob/master/Multiple%20Linear%20Regression%20predicting%20Cholesterol.pptx

Chris Park and Ben Johnson-Laird

National Health and Nutrition Examination Survey (NHANES) (2013-2016) 

16,881 survey respondents

Variables of Interest

Dependent Variable
Cholesterol - Chol

Independent Variables
Triglycerides - Trig
Body Mass Index - BMI
Blood Pressure - BP
Blood Urea Nitrogen - BUN
Age - Age
Gender
Race (7 Dummies)

Assumptions
Distribution of Residuals
QQ Plot - Normality Testing


Predicting Cholesterol with no interaction & no interpolation for missing values

Enhancements to the initial model

Log transformation of all continuous variables

Min-Max Scaling 

KNN Imputation of Missing Values

Interaction effect between age and BUN in predicting total cholesterol



Predicting Cholesterol with K nearest neighbor interpolation for missing values (k = 15)

Conclusion

Overall Adjusted-R2 Score increases after log transformation and normalization 

Both models were found to be statistically significant (p < 0.001)

Change in cholesterol levels were found to be different in older population


