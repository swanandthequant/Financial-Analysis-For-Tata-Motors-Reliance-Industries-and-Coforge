## Financial Analysis of Tata Motors, Reliance & Coforge

This repo contains a simple but usefull financial analysis notebook. It pulls stock price data for Tata Motors, Reliance Industries and Coforge from Yahoo Finance, and then does some basic portfolio level calculations.

## What this notebook does

### Loads Stock Data

1.Uses yfinance to get daily closing prices of

2.Tata Motors

3.Reliance Industries

4.Coforge

5.Nifty 50 (as benchmark)

### Data Cleaning

1.Drops any missing dates

2.Makes sure data is clean before doing analysis

### Calculates Daily Returns

1.Computes percentage change for each stock

2.Creates a simple portfolio with custom weights

3.Works out daily portfolio returns

### Portfolio Statistics

1.Annual return (compounded)

2. Annual volatility

3.Sharpe ratio (risk-adjusted return)

### Monte Carlo Simulation

1.Simulates thousands of future portfolio paths

2.Uses mean & volatility from historical returns

3.Shows final value distribution (5%, 25%, 50%, 75%, 95%)

4.Calculates probability of loss

5.Gives median CAGR & worst drawdown

### Visualization

1.Shows plots of stock prices and portfolio performance

## Files in this repo

Financial analysis for Tata motors, Reliance Industries, Coforge.ipynb
The main notebook with all code and analysis.

## What I Learned

1.How to use yfinance to get stock data

2.Building a portfolio with custom weights (0.4, 0.35, 0.25)

3.Calculating annual return, volatality and sharpe ratio

4.How to use Monte Carlo simulation to see possible future returns

## Note

This is just for practise, not finacial advise.
