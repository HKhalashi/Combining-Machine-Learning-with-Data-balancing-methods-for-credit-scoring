# Data Directory

This directory contains two datasets used in the credit scoring project:

## 1. UCI Credit Card Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)
- **Description**: This dataset includes information on default payments, demographic factors, credit data, payment history, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.
- **Number of Variables**: 25
- **Main Variables**:
  - `LIMIT_BAL`: Amount of given credit (NT dollars)
  - `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`: Demographic information
  - `PAY_0` to `PAY_6`: Repayment status from April to September 2005
  - `BILL_AMT1` to `BILL_AMT6`: Bill statement amounts from April to September 2005
  - `PAY_AMT1` to `PAY_AMT6`: Previous payment amounts from April to September 2005
  - `default.payment.next.month`: Whether the customer defaulted (1=yes, 0=no)
- **Acknowledgements**: Lichman, M. (2013). UCI Machine Learning Repository.

## 2. Default Dataset
- **Source**: [CRAN R Package ISLR](https://rdrr.io/cran/ISLR/man/Default.html)
- **Description**: A simulated dataset containing information on 10,000 customers aimed at predicting defaults on credit card debt.
- **Number of Variables**: 4
- **Main Variables**:
  - `default`: Whether the customer defaulted (Yes/No)
  - `student`: Whether the customer is a student (Yes/No)
  - `balance`: Average credit card balance after monthly payments
  - `income`: Customer's income
- **References**: James, G., Witten, D., Hastie, T., and Tibshirani, R. (2013). An Introduction to Statistical Learning.

For more details, please refer to the respective source links.

