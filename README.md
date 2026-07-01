# Institutional Portfolio Risk & Performance Dashboard

Interactive Python portfolio analytics dashboard for evaluating portfolio performance, risk, allocation, attribution, and diversification using real historical market data.

## Overview

This project is a Python-based portfolio risk and performance analytics platform designed to simulate the type of analysis used by investment analysts, portfolio managers, and risk teams.

The dashboard analyzes a diversified 30-holding portfolio across large-cap equities, mid-cap equities, small-cap equities, ETFs, bond ETFs, and commodity exposure. It uses historical market data to calculate portfolio returns, risk metrics, allocation exposures, performance attribution, correlation, rolling volatility, and drawdown.

The final output includes an interactive dashboard that allows users to explore key portfolio insights from one interface.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kayg44/Institutional-Portfolio-Risk-Performance-Dashboard/blob/main/Institutional_Portfolio_Risk_Performance_Dashboard.ipynb)

## Business Problem

Portfolio managers and investment teams need to understand not only whether a portfolio performed well, but also why it performed the way it did.

This project addresses questions such as:

- What was the portfolio's total and annualized return?
- How much risk did the portfolio take?
- What was the portfolio's Sharpe ratio?
- What was the largest drawdown?
- Which holdings performed best and worst?
- Which positions contributed most to overall portfolio return?
- How diversified is the portfolio across sectors and categories?
- How correlated are the holdings?
- How did portfolio volatility change over time?

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- ipywidgets
- Google Colab
- GitHub

## Portfolio Construction

The portfolio includes 30 holdings across multiple categories:

- Large-cap equities
- Mid-cap equities
- Small-cap equities
- Broad market ETFs
- Bond ETFs
- Commodity exposure

The portfolio is fully invested with weights summing to 100%.

## Key Features

### Performance Metrics

The dashboard calculates:

- Total return
- Annualized return
- Annualized volatility
- Sharpe ratio
- Maximum drawdown
- Growth of $1 invested

### Risk Analytics

The project includes:

- Portfolio drawdown analysis
- 30-day rolling annualized volatility
- Correlation matrix across holdings
- Sector and category concentration analysis

### Attribution Analysis

The dashboard separates standalone holding performance from weighted contribution to portfolio return.

This helps identify which securities had the largest impact on portfolio-level performance after accounting for position size.

### Allocation Analysis

The project evaluates portfolio exposure by:

- Sector
- Market-cap category
- Asset type

This supports diversification and concentration risk analysis.

### Interactive Dashboard

The final notebook includes an interactive dashboard built with `ipywidgets`, allowing users to select different views such as:

- KPI Dashboard
- Growth of $1
- Drawdown
- Rolling Volatility
- Sector Allocation
- Category Allocation
- Top Contributors
- Bottom Contributors

## Data Source

Historical market data is pulled using the `yfinance` Python package.

The analysis uses adjusted daily closing prices to calculate daily returns and portfolio-level performance.

## How It Works

1. Define a 30-holding portfolio with tickers, sectors, categories, and weights.
2. Download historical price data from Yahoo Finance using `yfinance`.
3. Calculate daily returns for each holding.
4. Apply portfolio weights to calculate daily portfolio returns.
5. Calculate performance and risk metrics.
6. Analyze allocation, attribution, correlation, drawdown, and rolling volatility.
7. Display final results through an interactive dashboard.

## Sample Outputs

The notebook produces:

- Portfolio performance summary table
- Growth of $1 invested chart
- Drawdown chart
- Sector allocation chart
- Category allocation chart
- Top and bottom performer tables
- Weighted contribution analysis
- Correlation matrix
- Rolling volatility chart
- Interactive KPI dashboard

## Skills Demonstrated

- Portfolio analytics
- Risk analysis
- Performance attribution
- Financial data analysis
- Python programming
- Data visualization
- Interactive dashboard development
- Investment research
- Market data analysis
- Pandas and NumPy
- yfinance data extraction

## Future Improvements

Potential future enhancements include:

- Adding benchmark comparison against the S&P 500
- Adding factor exposure analysis
- Adding value-at-risk calculations
- Adding downside deviation and Sortino ratio
- Adding user-controlled date ranges
- Adding portfolio optimization
- Building a Streamlit web app version
- Exporting reports to Excel or PDF

## Author

Kwasi Asante  
Finance | Data Analytics | Portfolio Analytics | Python
