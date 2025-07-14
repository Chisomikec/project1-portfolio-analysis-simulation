# Project 1: Stock Portfolio Analysis and Risk Forecasting

This project explores stock price behaviour and portfolio performance using real financial data. It combines statistical analysis, predictive modelling, and risk simulation to provide insights into investment performance and potential future outcomes.

---

## Project Overview

The notebook is structured into multiple stages:

### 1. **Stock Price Analysis**
- Analysed daily closing prices for selected stocks.
- Computed key statistics: **mean**, **median**, **standard deviation**, and **volatility**.
- Plotted **daily returns** and explored trends and variability.

### 2. **Portfolio Construction**
- Built two types of portfolios:
  - **Custom-weighted portfolio**
  - **Equally-weighted portfolio**
- Compared cumulative returns for both portfolios.
- Calculated **Sharpe ratio**, **maximum drawdown**, and **volatility** to assess performance.

### 3. **Prediction Task**
- Applied a **Linear Regression** model to predict daily returns.
- Performed **feature engineering** to enhance model input.
- Used a **Random Forest** model to evaluate **feature importance**.

### 4. **Monte Carlo Simulations (Bonus Task)**
Simulated 1000 possible future price paths using three different approaches:

| Method                        | Key Characteristic                                   |
|------------------------------|------------------------------------------------------|
| **Normal Distribution**      | Basic random walk assuming Gaussian returns.         |
| **Student’s t-Distribution** | Captures fatter tails and more extreme events.       |
| **Geometric Brownian Motion**| Models compounded growth with drift and volatility.  |

---

##  Folder Structure

```
Project1_Stock_Analysis/
│
├── figures/                    # saved diagrams for each method
├── stock_forecast_simulation.ipynb
└── README.md                 # this file
```

---

## Key Learnings
- The normal distribution is simple but fails to reflect rare extreme events.
- Student's t-distribution provides a better approximation for fat-tailed financial returns.
- GBM is commonly used in financial modelling and reflects exponential compounding.
- Prediction models benefit from feature engineering and interpretability checks.
- Portfolio metrics like Sharpe ratio and drawdown offer practical insights into risk-adjusted returns.

---

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `scipy`, `yfinance`

---

## Sample Visuals
All plots from each section (return analysis, prediction, simulation) are saved in the `figures/` directory.
