# Project4-ML

# Project Proposal: Analyzing the risk of credit card applicants
### Project Objective:
This project focuses on analyzing and predicting the risk levels of credit card applicants based on their demographic, financial, and application-related features. By utilizing machine learning techniques, the goal is to identify applicants who are "risky" or "not risky" based on patterns from historical data.

## Dataset Overview:
https://www.kaggle.com/code/rikdifos/credit-card-approval-prediction-using-ml

### Characteristics:
Gender <br>
Age<br>
Education Level<br>
Marital Status<br>
Income Total<br>
Income Type<br>
Housing Type<br>
Own Car (Yes/No)<br>
Own Realty (Yes/No)<br>
Own Phone (Yes/No)<br>
Family Members<br>
Employment Type<br>
Children Count<br>
Family Status

### Target Variable:
"Risky" <br>
Any of the applicants with the following:<br>
2: 60-89 days overdue  <br>
3: 90-119 days overdue  <br>
4: 120-149 days overdue  <br>
5: Overdue or bad debts, write-offs for more than 150 days <br> <br>
"Not Risky" <br>
Any of the applicants with the following:<br>
C: paid off that month 
X: No loan for the month
0: 1-29 days past due 
1: 30-59 days past due 



## Machine Learning Approach:
### Supervised Learning:
Build a classification model (logistic regression, decision tree, random forest, and neural networks) to predict risk/no risk based on data.
### Unsupervised Learning:
Use clustering algorithms (K-means, hierarchical clustering) to identify distinct groups of risky and non risky applicants who share similar characteristics and outcomes

## Potential Impact:
This project helps financial institutions improve decision-making for credit card approvals by accurately identifying high-risk applicants while minimizing defaults. The goal is to produce fair and data-driven decisions for applicants, increasing approval rates for low-risk individuals. 
