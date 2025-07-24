# 📈 Historical Stock and Revenue Data Dashboard

This project analyzes historical stock prices and revenue data of publicly listed companies using Python, and visualizes the trends in an interactive dashboard using Plotly.

## 🚀 Features

- Fetch historical stock data using the `yfinance` API
- Scrape revenue data using `BeautifulSoup` from MacroTrends
- Interactive dashboards with dual line plots: Share Price & Revenue
- Modular function (`make_graph`) for easy reuse with different stocks

## 🛠️ Technologies Used

- Python
- Pandas
- YFinance
- BeautifulSoup
- Plotly
- Jupyter Notebook

## 📊 Output Example

The dashboard contains:
- **Top Graph**: Company’s historical stock price over time
- **Bottom Graph**: Reported revenue trend from financial statements

## 🧠 How It Works

1. Get historical stock data using `yfinance`.
2. Scrape revenue data from MacroTrends using BeautifulSoup.
3. Combine and clean the data.
4. Visualize both using Plotly in a subplot layout.

## 🔍 How to Run

```bash
pip install pandas yfinance plotly beautifulsoup4 wget
