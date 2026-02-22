# Markowitz Portfolio Optimization

This project implements the **Modern Portfolio Theory (MPT)** developed by Harry Markowitz. It uses Python to find the optimal asset allocation by balancing the trade-off between risk and return.

## Features
- **Data Retrieval**: Automatically fetches historical financial data using the `yfinance` library.
- **Risk/Return Analysis**: Calculates expected annual returns and the covariance matrix of assets.
- **Optimization**: Computes optimal portfolio weights for a target risk/return profile.
- **Benchmark Comparison**: Compares the optimized portfolio against an "Equal Weight" strategy.

## Portfolio Composition
The model analyzes a diversified set of ETFs:
- **SPY** (S&P 500)
- **QQQ** (Nasdaq 100)
- **EFA** (MSCI EAFE - International Equities)
- **IWM** (Russell 2000 - Small Cap)
- **TLT** (20+ Year Treasury Bond)

## Requirements
To run this notebook, you need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `yfinance`
- `scipy` (for optimization functions)

## Results
The optimization process provides the specific weight for each asset to achieve the best performance, as shown in the notebook outputs (e.g., maximizing the Sharpe Ratio).
