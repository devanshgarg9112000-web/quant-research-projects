# JPM Gas Price Estimation

## Goal

This project estimates natural gas prices for given dates using historical monthly price data.

## Method

The project uses date-based features to estimate prices for past, present, and future dates. For dates between known observations, interpolation is used. For future dates, a regression-based approach is used with time and seasonal features.

## Key Features

- Monthly natural gas price data
- Date conversion into numeric features
- Price interpolation for known date ranges
- Future price estimation
- Linear Regression model
- Seasonal month-based features
- Simple pricing function for user input dates

## Tools Used

- Python
- Pandas
- NumPy
- scikit-learn

## Learning Outcome

This project helped me understand how time-based features and regression can be used for commodity price estimation.

## Note

This is an educational research project based on a virtual experience task and should not be treated as financial advice or a production pricing model.
