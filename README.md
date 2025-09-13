# Crypto-Quant-Trading-and-Analysis
Portfolio of exploratory quant analysis and strategy development for crypto assets

# Ethereum Return Stats 📈

A quant-style analysis of ETH daily returns (2019–2025).

## What this project does
- Fetches ETH price data using `yfinance`
- Cleans daily returns with Pandas
- Computes risk & return stats:
  - Mean/Std daily returns
  - Annualized return & volatility
  - Sharpe ratio
  - Max drawdown
- Visualizes performance with:
  - Cumulative return (equity curve)
  - Histogram of daily returns
  - Rolling volatility
  - Drawdown plot

## Results (2019–2025 sample)
- Annualized return: **135%**
- Annualized volatility: **82%**
- Sharpe ratio: **2.87**
- Max drawdown: *to be added*

## Next steps
- Add Sortino & Calmar ratios
- Add ETH–BTC correlation study
- Package functions into a reusable `analyze_strategy()` module
