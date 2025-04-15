# Newsparsing-and-stock-analysis
# 📊 AIDI1100 Final Project – Stock Analysis of Automotive Companies

## 🔍 Project Overview

This project aims to analyze news coverage and stock performance of automotive companies to help recommend the most promising stock for investment. We used web scraping, data analysis, and visualization techniques to extract insights over both short-term (30 days) and long-term (5 years) timeframes.

---

## 📂 Dataset Sources

- **News Headlines**: Scraped from [PR Newswire](https://www.prnewswire.com/news-releases/news-releases-list/)
- **Stock Data**: Retrieved using the `yfinance` API for symbols that appeared in the news
- **Selected Stocks**: Based on mentions in news – `GM (NYSE)`, `NIO (NYSE)`, and `MULN (NASDAQ)`

---

## 🧠 Technologies Used

- Python 🐍
- BeautifulSoup (for web scraping)
- Yahoo Finance API (`yfinance`)
- Matplotlib & Pandas (for data manipulation & plotting)
- Jupyter Notebook (.ipynb)
- PowerPoint (.pptx) for final presentation

---

## 📈 Analysis Steps

1. **Web Scraping**: Collected news headlines and counted mentions of 30+ automotive stock symbols.
2. **Stock Data Retrieval**:
   - Collected 30 days of stock data (Volume & Closing Price).
   - Also fetched 5 years of historical data to measure long-term returns.
3. **Visualization**:
   - Daily Volume and Close Price plots for selected stocks.
   - 5-Year normalized growth chart.
   - Bar chart comparing 5-Year return percentage.
4. **Recommendation**:
   - After analyzing 5-year performance, **General Motors (GM)** had the highest return (~95%) and was recommended as the best stock to buy among the selected ones.

---

## 🖼️ Final Outputs

- 📄 `news.csv`: Titles of scraped PR Newswire articles
- 📄 `selected_stocks_data.csv`: Last 30 trading days of price and volume data



---

## 🔗 GitHub Project Link

📌 [GitHub Repository](https://github.com/rak10095/Newsparsing-and-stock-analysis) 

---

## 👤 Team
Mahesh Sama​
Rakesh Kasaragadda​
Sarath Raju 
Rodrigo Rangel Alvarado ​
Saikrishna Mudaliar 

Course: AIDI_1100 -01​
Institution: Durham College​
Date: 14th,April 2025
