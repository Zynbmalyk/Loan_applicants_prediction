___________________________________________Task Objective__________________________________________

1) Reading, summarizing, and analyzing the loan applicant dataset
2)Learning to use pandas for data reading and exploration
3)Using matplotlib and seaborn for visualizations
5)Predicting which applicants are likely to default using Logistic Regression and Decision Tree

___________________________________________Approach_______________________________________________

Loaded dataset from local device using pandas.read_csv()
Explored dataset using head(), columns, shape and describe()
Checked for missing values dropna()
use crosstab(),bar(),Groupby() to check the proabilities 
Built Logistic Regression and Decision Tree models
Predicted default for sample new applicants

___________________________________Results & Insights____________________________________________

Dataset contains 255,347 rows (applicants)
Applicant income ranges from 15,000 to 149,999
Majority of applicants (25%–75%) have income between 48,825 and 116,219
Median income is 82,466
-------------------------------------------
Unemployed are highly at riak to be default and full time are at least.Output given below 
Employement Type vs default 
EmploymentType
Full-time         9.463366
Part-time        11.965213
Self-employed    11.462029
Unemployed       13.552895
----------------------------------------------
HIgh school are highly risked while masters and phd are least at risk 
Name: Default, dtype: float64
Education VS default 
Education
Bachelor's     12.101109
High School    12.878895
Master's       10.871721
PhD            10.585958
Name: Default, dtype: float64
--------------------------------------------
Accuracy of decision tree is higher than logistic regression 
logistic regression gives 57% while decision tree gives 79% accuracy 
