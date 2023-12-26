# Analyzing Depression Rates in MA
Create a linear regression model predicting depression as a function of various health, education, and income factors

![image](https://github.com/jeg-msba/depression_analysis/assets/111711622/5728c193-836c-49cc-ac1b-1ca54c88e8a2)

We started with 11 independent variables. We performed a backwords selection algoritm resulting in a final model 
using 3 variables: obesity, drinking, and medium household income. We created a log-linear model to better explain 
the results and also to create residual plots with more constant variance. Increases in the 
independent variables resulted in a predicted percent change in depression rate.
Obesity and binge drinking had a positive coefficent, household income had a negative coefficient.
The F statistic indicates the model is useful, with an Adjusted R-quared value of .647.
