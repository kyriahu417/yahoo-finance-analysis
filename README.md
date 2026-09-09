# Yahoo Finance Stock Analysis

This project applies data science and machine learning techniques to historical financial market data from Yahoo Finance. The analysis covers stock price exploration, technical indicators, trading strategy backtesting, predictive modeling, CAPM estimation, and portfolio optimization.

## Project Overview

The project begins with Apple (AAPL) for historical price analysis and moving-average strategies, then expands to multiple stocks for market-risk and portfolio analysis.

Key components include:

- Historical stock data retrieval and exploratory data analysis
- Moving average analysis and crossover trading signals
- Strategy backtesting against a buy-and-hold benchmark
- Machine learning models for next-day return direction prediction
- Model evaluation using accuracy, classification metrics, and confusion matrices
- CAPM alpha and beta estimation
- Efficient frontier construction and minimum-volatility portfolio optimization
- RSI-based mean reversion strategy and backtesting

## Tools & Technologies

- Python
- pandas
- NumPy
- yfinance
- scikit-learn
- statsmodels
- SciPy
- Matplotlib
- Seaborn

## Selected Results

The analysis highlights several practical considerations in financial data science:

- Simple moving-average strategies can generate positive historical returns while still underperforming buy-and-hold during strongly appreciating markets.
- Basic price-based features showed limited out-of-sample predictive power for next-day AAPL direction, illustrating the importance of evaluating models beyond accuracy alone.
- CAPM analysis revealed meaningful differences in market sensitivity across the selected stocks.
- Portfolio optimization demonstrated the trade-off between expected return and volatility across different asset allocations.
- An RSI-based mean reversion strategy outperformed buy-and-hold for NVDA over the selected historical sample period, although this result should not be interpreted as evidence of future performance.

## Methodology Notes

Time-dependent analyses use chronological train-test splitting and lagged trading signals to reduce look-ahead bias. Backtesting results are historical simulations and do not account for transaction costs, slippage, taxes, or other real-world implementation constraints.

## Project Notebook

The complete analysis, code, visualizations, and interpretation are available in:

`Yahoo_Finance_Project_Kyria_Hu.ipynb`

## Acknowledgment

This project was developed as part of the National Student Data Corps (NSDC) Data Science Projects program and subsequently refined and extended for portfolio presentation.
