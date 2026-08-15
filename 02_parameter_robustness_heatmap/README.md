# Parameter Robustness Heatmap

## Goal

This project tests multiple moving-average parameter combinations to check whether a trading strategy is robust or only works for one lucky parameter setting.

## Method

The project runs a loop over different fast and slow moving-average values. For each combination, it calculates strategy returns, final equity, Sharpe ratio, and maximum drawdown. The results are then organized into a table and visualized using a heatmap.

## Key Features

- Fast and slow moving-average parameter testing
- Strategy return calculation
- Sharpe ratio comparison
- Maximum drawdown comparison
- Parameter result table
- Heatmap visualization
- Robustness analysis

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib

## Learning Outcome

This project helped me understand that a strategy should not be trusted only because one parameter combination performs well. A stronger strategy should show stable performance across nearby parameter values.

## Note

This is an educational research project and should not be treated as investment advice or a production trading system.
