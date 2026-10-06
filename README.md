# Equity-Risk-Analysis-and-Portfolio-Optimization
End-to-end analysis of 10 Indian equities using risk-return metrics, CAPM, correlation, portfolio construction, minimum-volatility and maximum-Sharpe optimization, with Excel modelling and an interactive Power BI dashboard
# Equity Risk Analysis, Portfolio Construction & Optimization

## 📌 Project Overview

This project evaluates the risk and return characteristics of selected Indian equities and applies portfolio management techniques to construct and optimize investment portfolios.

The analysis combines **Python, Financial Analytics, Portfolio Theory, Excel, and Power BI** to move from individual stock analysis to portfolio construction and optimization.

The project focuses on:

- Individual stock risk-return analysis
- CAPM and systematic risk estimation
- Correlation and diversification analysis
- Portfolio construction
- Minimum Volatility Portfolio
- Maximum Sharpe Ratio Portfolio
- Equal Weight Portfolio
- Efficient Frontier analysis
- Portfolio performance comparison
- Interactive Power BI dashboard

The objective is to understand how different portfolio construction strategies affect **return, volatility, systematic risk, Sharpe Ratio, Treynor Ratio, and maximum drawdown**.

---

## 🎯 Project Objective

The primary objective of this project is to:

> **Evaluate selected Indian equities based on their historical risk-return characteristics, estimate systematic risk using CAPM, analyze diversification benefits, and construct optimized portfolios using risk and risk-adjusted return objectives.**

The project answers questions such as:

- Which stocks generated higher historical returns?
- Which stocks were more volatile?
- Which stocks had higher systematic risk?
- How strongly are the stocks correlated?
- How does diversification affect portfolio risk?
- What portfolio minimizes volatility?
- What portfolio maximizes the Sharpe Ratio?
- How do optimized portfolios compare with an Equal Weight portfolio?
- Which portfolio provides better risk-adjusted performance?

---

# 📊 Stock Universe

The analysis uses 10 major Indian listed companies across different sectors.

| Company | Ticker |
|---|---|
| HDFC Bank | HDFCBANK.NS |
| Reliance Industries | RELIANCE.NS |
| TCS | TCS.NS |
| Mahindra & Mahindra | M&M.NS |
| Adani Enterprises | ADANIENT.NS |
| JSW Steel | JSWSTEEL.NS |
| Sun Pharma | SUNPHARMA.NS |
| Bharti Airtel | BHARTIARTL.NS |
| Larsen & Toubro | LT.NS |
| Bajaj Finance | BAJFINANCE.NS |

### Benchmark

**NIFTY 50 (`^NSEI`)** is used as the market benchmark for CAPM analysis.

### Analysis Period

**January 2021 – January 2026**

The project uses daily market data for the analysis period.

---

# 🛠️ Tools & Technologies

### Python

Python is used for:

- Data collection
- Data cleaning
- Return calculations
- Risk calculations
- CAPM regression
- Correlation analysis
- Covariance matrix construction
- Portfolio optimization
- Random portfolio generation
- Efficient frontier analysis
- Visualization

### Python Libraries

- `pandas` – Data manipulation
- `numpy` – Numerical calculations
- `yfinance` – Market data collection
- `statsmodels` – OLS/CAPM regression
- `scipy.optimize` – Portfolio optimization
- `matplotlib` – Visualization

### Excel

Excel is used for:

- Portfolio weights
- Portfolio performance
- CAPM analysis
- Random portfolio results
- Financial model validation and presentation

### Power BI

Power BI is used to create an interactive dashboard for:

- Stock risk-return analysis
- Beta comparison
- Maximum drawdown comparison
- Portfolio comparison
- Portfolio allocation
- Efficient frontier visualization
- Dynamic portfolio KPIs

---

# 🔄 Project Methodology

The project follows the following analytical workflow:

```text
Market Data
     ↓
Data Cleaning & Validation
     ↓
Daily Returns
     ↓
Individual Stock Analysis
     ↓
Risk & Return Metrics
     ↓
CAPM Regression
     ↓
Correlation & Covariance Analysis
     ↓
Portfolio Construction
     ↓
Portfolio Optimization
     ↓
Historical Portfolio Evaluation
     ↓
Random Portfolio Simulation
     ↓
Efficient Frontier Analysis
     ↓
Power BI Dashboard
