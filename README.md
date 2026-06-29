#Market Risk Analytics in Python

#A comprehensive quantitative finance toolkit implementing industry-standard techniques for market risk measurement, volatility forecasting, portfolio analytics, and derivatives pricing.

---

# Overview

This project demonstrates the implementation of key quantitative finance models commonly used in investment banks and financial institutions for market risk measurement and portfolio analytics.

The notebook combines statistical modelling, financial theory, and numerical methods to analyze equity markets, estimate portfolio risk, model volatility, price derivative securities, and perform simulation-based risk analysis.

The objective is to build an end-to-end market risk analytics toolkit using Python.

---

# Project Modules

## 1. Market Data Analysis

- Historical market data collection
- Data cleaning & preprocessing
- Log return computation
- Return visualization
- Summary statistics

---

## 2. Volatility Modelling

Implemented multiple approaches for estimating asset volatility.

### Models

- Historical Volatility
- Exponentially Weighted Moving Average (EWMA)
- GARCH(1,1)
- EGARCH

These models are widely used for volatility forecasting and risk management within financial institutions.

---

## 3. Capital Asset Pricing Model (CAPM)

Estimated systematic risk using CAPM.

Implemented:

- Beta estimation
- Expected return calculation
- Security Market Line
- Market vs Asset return comparison

---

## 4. Value at Risk (VaR)

Implemented industry-standard portfolio risk measures.

### Methods

- Historical Simulation VaR
- Parametric (Variance-Covariance) VaR

Risk estimates are computed across different confidence levels to measure potential portfolio losses under normal market conditions.

---

## 5. Option Pricing

Implemented the Black-Scholes option pricing framework.

Calculated option prices for:

- European Call Options
- European Put Options

---

## 6. Option Greeks

Computed the primary option sensitivity measures.

- Delta
- Gamma
- Vega
- Theta
- Rho

These measures are fundamental for derivatives risk management and hedging strategies.

---

## 7. Monte Carlo Simulation

Simulated asset price paths using Geometric Brownian Motion.

Applications include:

- Stock price simulation
- Option pricing
- Scenario analysis
- Risk estimation

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- yfinance
- statsmodels
- arch
- py_vollib

---

# Financial Concepts Covered

- Market Risk
- Portfolio Analytics
- Volatility Forecasting
- Capital Asset Pricing Model (CAPM)
- Beta Estimation
- Value at Risk (VaR)
- Black-Scholes Model
- Option Greeks
- Monte Carlo Simulation
- Quantitative Finance

---

# Key Skills Demonstrated

- Financial Data Analysis
- Risk Analytics
- Quantitative Modelling
- Statistical Analysis
- Portfolio Risk Measurement
- Derivatives Analytics
- Financial Python Programming

---

# Repository Structure

```
Market-Risk-Analytics/
│
├── Market_Risk_Analytics_Python.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

# Results

The notebook provides:

- Historical return analysis
- Volatility forecasts
- CAPM estimation
- Portfolio Value at Risk calculations
- Black-Scholes option valuation
- Option Greeks
- Monte Carlo simulated price paths

The project demonstrates the practical application of quantitative finance techniques frequently used in market risk, trading, and investment analytics.

---

# Applications

This project is relevant to roles in:

- Market Risk
- Quantitative Finance
- Risk Analytics
- Portfolio Management
- Treasury
- Investment Banking
- Asset Management
- Financial Engineering

---

# Future Improvements

- Expected Shortfall (CVaR)
- Stochastic Volatility Models
- Heston Model
- Credit Risk Modelling
- Interest Rate Models
- Stress Testing Framework
- Portfolio Optimization Integration

---

# Author

**Shaashwat Dhar**

BITS Pilani, Hyderabad Campus

B.E. Mechanical Engineering & M.Sc. Economics

LinkedIn: https://linkedin.com/in/shaashwat-dhar-084761201

GitHub: https://github.com/shaashwatdhar123
