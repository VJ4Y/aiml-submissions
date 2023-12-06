# Lending Club Case Study


## Libraries Used:
- numpy
- pandas
- matplotlib.pyplot
- seaborn


## Problem Statement:

Given a loan data set of a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan , then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

## Observations:

### From the above analysis e probability of  loan defaulting is when : 

- When the loan is verified and loan amount is above 16k and loan is not verified for loan amount below 8.5k
- Applicants taking loan for 'home improvement' and have income of 60k -70k and home ownership is 'MORTGAGE
- Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k and who receive interest at the rate of     5-9% and have an income of 50k-60k
- For grade G and interest rate above 20%
- When employment length is 10yrs and loan amount is 12k-14k 
- Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
- Applicants who have taken a loan for small business and the loan amount is greater than 14k
- Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k
- When grade is F and loan amount is between 15k-20k
- When home ownership is Rent, more than 2500 applicants are charged off
- Applicants with debt consolidation are loan defaulters
- 12k - 14k applicants have received interest rate of 9-13%
- Maximum number of defaulters occured when the loan was sanctioned/issued in the month of december and issued in year 2011