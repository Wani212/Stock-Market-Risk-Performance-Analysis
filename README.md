# Stock Market Risk & Performance Analysis

## Overview

This project analyzes the historical performance and risk characteristics of selected equities and the S&P 500 ETF (SPY) using Python, Pandas and Microsoft Power BI.

The objective was to evaluate investment performance using multiple financial metrics rather than relying on returns alone.

## Assets Analyzed

- AAPL
- AMZN
- GOOGL
- JPM
- MSFT
- NVDA
- SPY
- TSLA

## Analysis Period

2020–2026

## Tools & Technologies

- Python
- Pandas
- NumPy
- Power BI
- DAX
- Power Query
- Excel

## Key Metrics

### Performance
- CAGR
- Annualized Return
- Indexed Performance
- Monthly Returns

### Risk
- Annualized Volatility
- Maximum Drawdown

### Risk-Adjusted Performance
- Sharpe Ratio

### Diversification
- Return Correlation Matrix

## Key Findings

### NVDA

- CAGR: 73.22%
- Annualized Volatility: 51.97%
- Maximum Drawdown: -63.34%
- Sharpe Ratio: 1.32

### TSLA

- CAGR: 45.60%
- Annualized Volatility: 64.96%
- Maximum Drawdown: -73.63%
- Sharpe Ratio: 0.90

NVDA produced the stronger historical return and risk-adjusted performance of the two assets analyzed, while TSLA experienced higher volatility and a deeper maximum drawdown.

The analysis demonstrates that evaluating an asset based only on historical return can overlook significant differences in risk.

## Dashboard

The Power BI dashboard contains three sections:

### 1. Investment Overview
- KPI summary
- Risk vs. return analysis
- Indexed performance
- Monthly returns
- Annualized returns
- ![Investment Overview](https://github.com/Wani212/Stock-Market-Risk-Performance-Analysis/blob/main/Stock%20Market%20Analysis/screenshots/Screenshot%202026-08-31%20062032.png)
### 2. Risk Analysis
- Annualized volatility
- Maximum drawdown
- Sharpe ratio
- Risk vs. return
- Correlation matrix

### 3. Investment Performance & Insights
- Indexed investment performance
- Monthly return trends
- Key analytical findings
- Methodology

## Methodology

Historical market data was cleaned and transformed using Python/Pandas.

Financial metrics were calculated from the historical price data and summarized for comparison in Power BI.

The Sharpe ratio was calculated using a 0% risk-free rate assumption.

SPY was included as a benchmark for comparison with the individual equities.
