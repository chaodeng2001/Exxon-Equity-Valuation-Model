# Exxon Equity Valuation Model

This project is a Python-based valuation model for Exxon Mobil (XOM) using financial data pulled from Yahoo Finance through the `yfinance` library.

The model combines several core finance methods to estimate Exxon’s intrinsic value and analyze how valuation changes under different oil-price and discount-rate assumptions.

## Features

- Pulls Exxon financial data automatically using `yfinance`
- Builds a simplified **Discounted Cash Flow (DCF)** model
- Uses **Comparable Company Analysis** with major energy peers
- Runs **Bull / Base / Bear scenario analysis**
- Creates a **sensitivity table** for oil price and WACC
- Visualizes how Exxon’s implied value changes as oil prices move

## Models Included

### 1. Discounted Cash Flow (DCF)
The model forecasts Exxon’s free cash flow over a 5-year period and discounts it back to present value using WACC.

### 2. Comparable Company Analysis
The project compares Exxon to peer companies such as Chevron, ConocoPhillips, Occidental, BP, and Shell using EV/EBITDA multiples.

### 3. Scenario Analysis
The model tests different valuation outcomes under:
- Bear case
- Base case
- Bull case

### 4. Sensitivity Analysis
The model shows how Exxon’s valuation changes based on:
- Oil price assumptions
- WACC assumptions

## Why This Project

Energy equities are strongly influenced by commodity prices, capital intensity, and macro conditions. This project was built to combine Python automation with core equity valuation techniques in order to analyze an energy stock in a more practical and industry-relevant way.

This project is designed to demonstrate:
- Python for financial analysis
- Automated data collection
- Equity valuation methods
- Energy-sector-specific modeling
- Scenario and sensitivity analysis

## Tools and Libraries

- Python
- yfinance
- pandas
- numpy
- matplotlib

## Project Structure

```bash
exxon-equity-valuation-model/
│
├── exxon_valuation.py
├── README.md
└── requirements.txt
