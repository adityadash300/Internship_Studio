# Internship_Studio
## Machine Learning Internship

## Problem
### Context
The bank has a growing customer base. The bank wants to increase borrowers (asset
customers) base to bring in more loan business and earn more through the interest on
loans. So , the bank wants to convert the liability based customers to personal loan
customers. (while retaining them as depositors). A campaign that the bank ran last year
for liability customers showed a healthy conversion rate of over 9% success. The
department wants you to build a model that will help them identify the potential
customers who have a higher probability of purchasing the loan. This will increase the
success ratio while at the same time reduce the cost of the campaign.

### Objective
The classification goal is to predict the likelihood of a liability customer buying personal
loans.

**************

## Attribute Information of Dataset
- ID: Customer ID
- Age: Customer's age in completed years
- Experience: #years of professional experience
- Income: Annual income of the customer
- ZIP Code: Home Address ZIP code.
- Family: Family size of the customer
- CCAvg: Avg. spending on credit cards per month ($000)
- Education: Education Level 1: Undergrad<br>
 Level 2: Graduate <br>Level 3:
Advanced/Professional

- Mortgage: Value of house mortgage if any.
- Personal Loan: Did this customer accept the personal loan offered in the last
campaign?
- Securities Account: Does the customer have a securities account with the bank?
- CD Account: Does the customer have a certificate of deposit (CD) account with
the bank?
- Online: Does the customer use internet banking facilities?
- Credit card: Does the customer use a credit card issued by the bank?

******************

This project uses various models alongwith **Logistic Regression**.

Following are the inferences found in this project:

- The Data is not perfectly linear as accuracy in case of **Logistic Regression** is less than other classifiers.


- The accuracy of Bayesian Model is low which means the actual probability of obtaining the target class is low.


- *Decision Tree* has by far given maximum accuracy in test and train set.


- The graphical representation of *Decision Tree* can give insights about the classification method
