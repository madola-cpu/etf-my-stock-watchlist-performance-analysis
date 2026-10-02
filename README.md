
##ETF and Stock Watchlist Performance Analysis

## Project overview

This project analyzes and compares the historical performance of selected ETFs and individual stocks. 
The goal is to apply data analysis and finacial analysis techniques to evaluate return, risk, volatility, correlations and overall performance across different investment.

#Assets

## ETFs
VOO,
VXUS,
SCHD,
VNQ,
QQQM,
FXAIX (It's the Fidelity 500 Index Fund, a mutual fund. That also explains the unusual volume behavior you noticed.)

### Stocks
AMZN,
AAPL,
MSFT,
NVDA

##  tools
Python,
Excel,
SQL,
Tableau,
Git $ Github

## Project Status
work in progress

## Project Workflow

### 1. Data Collection
Historical market data is retrieved from Yahoo Finance using `yfinance`.

The collection pipeline uses a rolling five-year window so that rerunning the notebook retrieves the most recent five years of available market data.

### 2. Data Cleaning and Preparation
The raw Yahoo Finance data is validated and transformed from a wide MultiIndex structure into a long, analysis-ready dataset.

Data quality checks include:

- Missing values
- Duplicate observations
- Ticker coverage
- Date coverage
- Invalid price values
- Observation counts by security

The cleaned dataset contains one observation per ticker per trading date.

### 3. Performance Analysis
Coming next.

### 4. SQL Analysis
Planned.

### 5. Excel & Tableau
Planned.













