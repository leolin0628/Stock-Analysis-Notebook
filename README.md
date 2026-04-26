# Stock Analysis Notebook

A Python notebook for analyzing individual stock performance using historical market data. Currently covers **NVIDIA (NVDA)**, with more stocks to be added over time.

## What It Does

Given a stock ticker, the notebook pulls historical price data and walks through a full quantitative analysis:

- **Price Trends** — plots closing price over the past year
- **Returns Analysis** — calculates daily and annualized returns
- **Volatility Analysis** — measures daily and annualized volatility, with a distribution plot of daily returns
- **Risk-Adjusted Performance** — computes the Sharpe Ratio to evaluate returns relative to risk
- **Technical Indicators** — plots 20-day and 50-day moving averages
- **Business & Valuation Overview** — qualitative summary of the company's financials and a simple buy/sell/hold conclusion

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
2. Open `stock_analysis.ipynb` in Jupyter Notebook or VS Code
3. Change the `ticker` variable at the top to any stock you want to analyze
4. Run all cells

## Planned Additions

- DCF (Discounted Cash Flow) valuation model
- Multi-stock comparison
- Additional technical indicators