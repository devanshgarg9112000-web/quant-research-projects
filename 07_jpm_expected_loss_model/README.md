# JPM Expected Loss Model

## Goal

This project estimates the expected loss on a loan by predicting the probability of borrower default.

## Method

The project uses borrower information such as loan amount, income, debt, years employed, credit lines outstanding, and FICO score. A Logistic Regression model is trained to estimate the probability of default. Expected loss is then calculated using probability of default, loan amount, and loss given default.

## Formula

Expected Loss = Probability of Default × Loan Amount × Loss Given Default

## Key Features

- Borrower credit-risk dataset
- Train/test split
- Logistic Regression model
- Probability of default prediction
- Recovery rate assumption
- Loss given default calculation
- Expected loss calculation
- Borrower-level risk estimation function

## Tools Used

- Python
- Pandas
- NumPy
- scikit-learn

## Learning Outcome

This project helped me understand how machine learning can be used in credit-risk modeling, especially for probability of default and expected loss estimation.

## Note

This is an educational research project based on a virtual experience task and should not be treated as a production credit-risk model.
