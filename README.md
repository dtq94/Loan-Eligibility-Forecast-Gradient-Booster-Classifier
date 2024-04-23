# Loan Default Prediction: GBM

## Project Overview
Predicting loan defaults is crucial for financial institutions to mitigate risks and optimize lending strategies. This project compares the performance of Linear Regression and XGBoost models in predicting loan defaults using historical loan data.

## Data Description
The dataset consists of loan information with the following fields:
- Loan ID: Unique identifier for loan information.
- Customer ID: Unique identifier for the customer. Customers may have multiple loans.
- Loan Status: Categorical variable indicating if the loan was given to this customer.
- Current Loan Amount: Loan amount either paid off or defaulted.
- Term: Categorical variable indicating short or long term loan.
- Credit Score: Riskiness of borrower’s credit history.
- Years in Current Job: Years the customer has been in their current job.
- Home Ownership: Categorical variable indicating home ownership.
- Annual Income: Customer's annual income.
- Purpose: Description of the purpose of the loan.
- Monthly Debt: Customer's monthly payment for existing loans.
- Years of Credit History: Years since the first entry in customer’s credit history.
- Months since Last Delinquent: Months since the last loan delinquent payment.
- Number of Open Accounts: Total number of open credit cards.
- Number of Credit Problems: Number of credit problems in customer records.
- Current Credit Balance: Current total debt for the customer.
- Maximum Open Credit: Maximum credit limit for all credit sources.
- Bankruptcies: Number of bankruptcies.
- Tax Liens: Number of tax liens.

## Tech Stack
- fancyimpute==0.7.0
- imblearn==0.0
- joblib==1.3.1
- matplotlib==3.7.2
- numpy==1.24.4
- pandas==1.3.5
- scikit_learn==1.3.0
- scipy==1.10.1
- seaborn==0.12.2
- six==1.16.0
- xgboost==1.7.6

