# Monte Carlo Options Pricing Engine

A Python-based options pricing tool that calculates theoretical call option prices 
and Greeks using Monte Carlo simulation, benchmarked against Black-Scholes analytical pricing.

## Features
- Monte Carlo simulation for call option pricing using log-normal return modeling
- Greeks calculation (Delta) via numerical differentiation
- Risk-neutral pricing framework
- Benchmarking against Black-Scholes closed-form solution
- Delta hedging signal generation with automated mispricing detection (>5% edge)
- Real-time market data via yfinance
- Alpaca Markets API integration for paper trading (in progress)

## Tech Stack
Python, NumPy, pandas, yfinance, Alpaca API

## Usage
Clone the repo and run the main pricing script with a ticker and options parameters.
