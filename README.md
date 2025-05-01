## Indian Stock Portfolio Performance Analysis
This project analyzes the performance of a sample Indian stock portfolio using Python and financial data retrieved from Yahoo Finance. It calculates and visualizes key performance metrics such as annualized returns, volatility, cumulative returns, and the Sharpe ratio.

---

## 📊 Overview
The notebook:
- Downloads historical stock price data for a selected portfolio of Indian equities (e.g., RELIANCE, TCS, HDFC Bank) using `yfinance`
- Cleans and processes the data
- Computes portfolio metrics such as:
  - Annualized Return
  - Annualized Volatility
  - Sharpe Ratio
  - Cumulative Returns
- Generates visualizations using `matplotlib` and `seaborn`

---

## 🛠️ Technologies Used
- Python
- yfinance
- pandas
- numpy
- matplotlib
- seaborn

---

## 📈 Portfolio Metrics Calculated
- **Annualized Return**: Mean return scaled to yearly performance
- **Annualized Volatility**: Risk or standard deviation scaled to a yearly basis
- **Sharpe Ratio**: Risk-adjusted return (assuming a risk-free rate of 6.8%)
- **Cumulative Returns**: Total return over time

---

## 🗂️ Project Structure
- `Indian Stock Portfolio Performance Analysis.ipynb`: Main notebook with all analysis steps
- `portfolio_data.csv`: Saved cleaned price data (generated during execution)

---

## ✅ Results Summary
- Annualized Portfolio Return: `0.0304`
- Annualized Volatility: `0.1570`
- Sharpe Ratio: `-0.2393`

- Annualized Portfolio Return (3.04%):
This is the average return your portfolio would generate per year, assuming the same performance continues. A 3.04% return is relatively modest, and below typical market benchmarks like the Nifty 50 or S&P 500 long-term averages (~8–10%).
- Annualized Volatility (15.70%):
This reflects the portfolio's risk or price fluctuation. A 15.7% annual volatility is moderate—indicative of normal market swings—but should be compared to the volatility of alternative investments or your risk tolerance.
- Sharpe Ratio (-0.2393):
This is a key concern. A negative Sharpe ratio means your portfolio underperformed relative to a risk-free investment (e.g., fixed deposit, assumed at 6.8%) after adjusting for risk. This suggests that for the level of risk taken, you’d have been better off with a risk-free investment.

---

## 📌 Notes
- The default portfolio contains 3 equally weighted stocks: `RELIANCE.NS`, `TCS.NS`, `HDFCBANK.NS`.
- You can modify the stock list and weights in the notebook for your own portfolio.
