# Mental-health-project
This project is an analysis of a dataset from Kaggle. My analysis had the following steps:
1. First, I loaded and inspected the dataset, checking for NAs and descriptions.
2. Second, I made an array with all the unique values to inspect if values were correctly imputed.
3. Third, I made dummy variables for all the categorical variables and all bools numerical.
4. Fourth, I made some graphical representations of the dataset ( for gender, age distribution, university count, degree (graduate/undergraduate) count, primary count, and GPA count)
5. Fifth, I completed a regression with Depression as the dependent variable (scale of 1 to 5), dropped statistically insignificant variables, and reran the regression. 
The result was a model that had an adjusted R-squared of 0.967 and <0.01 significance.
The correlation coefficients were: Undergrad (-0.68), Sports engagement (-0.516), Academic year 3 (-0.282), Isolation (0.248), Academic workload (0.286), and anxiety (0.683)
In conclusion, to keep the risk of depression low, engage in sports, don't isolate yourself, have a low academic workload, and try to manage anxiety. Additionally, it would help to be in your third year of undergraduate studies.
