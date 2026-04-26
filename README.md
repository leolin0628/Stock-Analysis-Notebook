# Stock Analysis Notebook

A Python notebook series for analyzing individual stock performance using historical market data. Each notebook covers a specific stock with both quantitative analysis and a written investment overview.

## Current Coverage

| Stock | Ticker | Notebook |
|-------|--------|----------|
| NVIDIA | NVDA | `stock_analysis_nvda.ipynb` |

## What Each Notebook Does

- **Price Trends** — plots closing price over the past year
- **Returns Analysis** — calculates daily and annualized returns
- **Volatility Analysis** — measures daily and annualized volatility, with a distribution plot of daily returns
- **Risk-Adjusted Performance** — computes the Sharpe Ratio to evaluate returns relative to risk
- **Technical Indicators** — plots 20-day and 50-day moving averages
- **Business & Valuation Overview** — written analysis of the company's financials and a buy/sell/hold conclusion (stock-specific, not auto-generated)

## Libraries Used

```
yfinance
pandas
numpy
matplotlib
```

Install them with:

```bash
pip install yfinance pandas numpy matplotlib
```

## How to Run

1. Clone the repo
2. Open the notebook for the stock you want in Jupyter Notebook or VS Code
3. Run all cells

## Planned Additions

- DCF (Discounted Cash Flow) valuation model
- Additional stocks
- Multi-stock comparison
