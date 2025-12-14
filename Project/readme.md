# Risk Parity Portfolio Project

## Project Overview
This project explores the concept of **Risk Parity**, a portfolio management strategy that allocates capital based on risk (volatility) rather than dollar amount. The goal is to equalize the risk contribution of each asset to the overall portfolio.

In this project, we implement a risk-parity strategy using Python to:
- Download financial data for **S&P 500 Futures**, **10-Year Treasury Futures**, **Gold Futures**, and the **US Dollar Index**.
- Resample data to a monthly frequency.
- Compute rolling volatility and risk-parity weights.
- Calculate portfolio returns and verify performance using metrics like **Sharpe Ratio**, **Sortino Ratio**, and **Maximum Drawdown**.

## Key Features
- **Data Collection**: Automatic download of futures data using `yfinance`.
- **Data Processing**: Monthly resampling and cleaning of financial time series.
- **Risk Analysis**: Rolling volatility calculation (36-month window).
- **Portfolio Optimization**: Inverse-volatility weighting scheme.
- **Performance Evaluation**: Comprehensive metrics (Annualized Return, Volatility, Sharpe, Sortino, Calmar, Max Drawdown).
- **Visualization**: Cumulative returns and drawdown plots.

## Files
- `projectv2.ipynb`: The main notebook containing the implementation and analysis.
- `../rubric_verification.md`: A report comparing the implementation against the project rubric.

## Dependencies
- `pandas`
- `numpy`
- `yfinance`
- `matplotlib`
