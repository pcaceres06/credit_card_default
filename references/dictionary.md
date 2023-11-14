# Lending Club Loan Data Analysis

[Link to the dataset](https://www.kaggle.com/datasets/deependraverma13/lending-club-loan-data-analysis-deep-learning/data)

## About Dataset

Problem Statement:

For companies like Lending Club correctly predicting whether or not a loan will be a default is very important. In this project, using the historical data from 2007 to 2015, you have to build a deep learning model to predict the chance of default for future loans. As you will see later this dataset is highly imbalanced and includes a lot of features that make this problem more challenging.


| **Variable Name** | **Data Type** | **Description**                                                                                                                                                                 |
|:-----------------:|:-------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| credit.policy     | Boolean       | 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise                                                                                    |
| purpose           | String        | The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other")                                  |
| int.rate          | Float         | The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates |
| installment       | Float         | The monthly installments owed by the borrower if the loan is funded                                                                                                             |
| log.annual.inc    | Float         | The natural log of the self-reported annual income of the borrower                                                                                                              |
| dti               | Float         | The debt-to-income ratio of the borrower (amount of debt divided by annual income)                                                                                              |
| fico              | Integer       | The FICO credit score of the borrower                                                                                                                                           |
| days.with.cr.line | Float         | The number of days the borrower has had a credit line                                                                                                                           |
| revol.bal         | Integer       | The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle)                                                                                    |
| revol.util        | Float         | The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available)                                                          |
| inq.last.6mths    | Integer       | The borrower's number of inquiries by creditors in the last 6 months                                                                                                            |
| delinq.2yrs       | Integer       | The number of times the borrower had been 30+ days past due on a payment in the past 2 years                                                                                    |
| pub.rec           | Integer       | The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments)                                                                                |
| not.fully.paid    | Boolean       | Target variable, 1 if the customer fully pay the credit 0 otherwise                                                                                                             |