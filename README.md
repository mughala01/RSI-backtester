# RSI-backtester
RSI Backtester fetches historical stock data, calculates the 14-day Relative Strength Index (RSI), and generates buy/sell signals. Includes visualizations of closing price and RSI with overbought/oversold levels. Ideal for learning technical analysis and building quant strategies

# RSI Backtester

A beginner-friendly RSI (Relative Strength Index) backtesting project in Python. This project fetches historical stock data, calculates the 14-day RSI, generates simple buy/sell signals, and visualizes results with matplotlib.

## Features
- Fetches historical stock data via `yfinance`
- Calculates RSI and adds trading signals:
  - Buy when RSI < 30 (oversold)
  - Sell when RSI > 70 (overbought)
- Plots closing price and RSI with overbought/oversold lines
- Simple, beginner-friendly Python code

## Installation
1. Clone this repository:
```bash
git clone <your-repo-url>

