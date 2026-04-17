# Stock Portfolio Analysis with Benchmark Comparison (Excel)

## Overview
This project analyzes a stock portfolio using Microsoft Excel. It evaluates performance relative to a market benchmark (S&P 500 via SPY) using return, volatility, and excess return metrics.

---

## Data Preparation
- Imported time-series stock price data (AAPL, MSFT, TSLA, AMZN, SPY)
- Cleaned messy data:
  - Replaced invalid values ("N/A", "missing")
  - Handled missing values using forward-fill
- Structured dataset for time-series analysis

---

## Calculations

### Daily Return
Return = (Price_t / Price_(t-1)) - 1

### Portfolio Return (Equal Weight)
Portfolio Return = Σ (Weight_i × Return_i)  
(Each asset weighted at 20%)

### Excess Return
Excess Return = Portfolio Return - Benchmark Return (SPY)

### Average Return
Average Return = AVERAGE(Return_t)

### Volatility (Risk)
Volatility = STDEV(Return_t)

---

## Key Results
- Avg Portfolio Return: **0.61%**
- Avg Benchmark (SPY): **0.34%**
- Excess Return: **0.28%**
- Portfolio Volatility: **~1%**

---

## Conclusion
The portfolio outperformed the S&P 500 benchmark while maintaining moderate volatility, indicating strong risk-adjusted performance. Diversification across assets helped stabilize returns while still achieving excess performance over the market.

---

## Tools Used
- Microsoft Excel  
- Data cleaning techniques  
- Financial analysis (returns, volatility, benchmarking)

---
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/186d5c9d-4a4a-4846-8b7a-15962074bf10" />
