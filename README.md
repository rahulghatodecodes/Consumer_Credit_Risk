# Consumer Credit Risk

## Overview
The data frame contains of 10k customers having records of whether customers defaulted on their credit card debt or not. We can break down the data frame into 4 variables:
- Default:  A factor with levels No and Yes indicating whether the customer defaulted on their debt.
- Student:  A factor with levels No and Yes indicating whether the customer is a student.
- Balance:  The average balance that the customer has remaining on their credit card after making their monthly payment. If the customer has borrowed $3000, repaid $1000 and not repaid $2000(outstanding balance)
- Income:   Monthly Income of customer.

We have two categorical columns(Default, Student) and two numerical columns(Balance, Income).


## Objective
- Perform Exploratory Data Analysis
- Implement a Logistic Regression Model

## Programming Language & Tools
- Python 
- Jupyter Notebook
- MS Excel

## Actions
- Checked the basic measures of descriptive statistics for the continuous variables(Balance, Income) and the statistics of categorical variables(Student, Default).
- Creating Boxplots.
- Carried out Univariate Analysis and Bivariate Analysis.
- Checked for correlation between independent variables. 
- Checked the missing values. 
- Treated outliers present in the ’balance’ variable.
- Converted Categorical Variables to Numeric variables.
- Created train and test set.
- Created a confusion matrix.

## Inferences
- Defaulters seem to have higher outstanding balance compared non-defaulters. 
- Few customers have probably borrowed a small amount and not been able to pay back the small amount. If the customer has borrowed around $1000, repaid $300 and not repaid $700 (outlier).
- Whether the person defaults or not, the average income probably seems to be the same.
- The range of income is higher for those who do not default.
- If the person is not a student, then there is 97% chance the person will not default and 3% chance the person will default.
- If the person is a student, then there is 96% chance the person will not default and 4% chance the person will default.
- Correlation between two numerical columns(balance & income), not much correlation found.

## Results
Implemented logistic Regression model. Accuracy of the model was 88%.



