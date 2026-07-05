# 📈 AI Stock Research Screener

An AI-powered stock research and screening tool for US and Indian equities. This project fetches live financial data, computes key investment metrics, screens stocks based on customizable criteria, generates professional equity research reports using Google's Gemini API, and exports results to Excel.

---

## 🚀 Features

- 🌎 Supports US and Indian (NSE) stocks
- 📊 Live market data using Yahoo Finance
- 📈 Revenue CAGR (5 Years)
- 💰 Gross Margin, Net Margin, ROE
- 🏦 Debt-to-Equity & Current Ratio
- 📉 Annualized Volatility
- 🛡 Risk Score (1–10)
- 🏰 Quantitative Moat Rating
- 💵 Dividend Analysis
- 🎯 Bull & Bear Price Targets
- 🤖 AI-generated Equity Research Reports (Google Gemini)
- 📄 Excel Export
- 📊 Data Visualization

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Stock-Research-Screener.git

cd AI-Stock-Research-Screener
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebooks/stock_screener.ipynb
```

---

## ▶ Usage

Enter stock tickers when prompted.

Example

```
AAPL,MSFT,NVDA,TSLA,RELIANCE.NS,TCS.NS
```

The notebook automatically

- Downloads financial data
- Calculates investment metrics
- Screens stocks
- Generates AI research reports
- Exports Excel reports


---


---

## Equity Research Reports

Generates comprehensive equity research reports using real-time market data, financial metrics, valuation analysis, risk assessment, analyst price targets, and AI-powered insights.

<p align="center">
  <img src="images/tcs_report.png" alt="TCS Equity Research Report" width="48%">
  <img src="images/meta_report.png" alt="Meta Equity Research Report" width="48%">
</p>

---

## 📈 Stock Performance Comparison

Compares the historical price performance of selected stocks over a specified time period.

<p align="center">
  <img src="images/performance_comparison.png" width="85%">
</p>

---

## 📉 Risk vs Return Analysis

Visualizes the relationship between annualized returns and volatility to support investment risk assessment.

<p align="center">
  <img src="images/risk_return_scatter.png" width="85%">
</p>

---

## 🌐 Sector Performance Heatmap

Highlights sector-wise performance to provide a quick overview of market trends and relative strength.

<p align="center">
  <img src="images/sector_heatmap.png" width="85%">
</p>

---

## 🎯 Financial Radar Chart

Compares key financial indicators such as profitability, growth, valuation, and financial health across selected companies.

<p align="center">
  <img src="images/radar_chart.png" width="85%">
</p>

---

## 🏆 Composite Stock Ranking

Ranks stocks using a custom composite scoring model based on valuation, growth, profitability, dividends, and risk metrics.

<p align="center">
  <img src="images/leaderboard.png" width="85%">
</p>

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- yfinance
- GROQ API
- OpenPyXL
- Matplotlib