# Stock-Revenue-Dashboard-Analysis

📈 Final project for IBM Data Analysis with Python (Coursera) — extracting and visualizing stock & revenue data for Tesla and GameStop using yfinance, web scraping, and Matplotlib.

---

## 📌 Project Overview

This project takes on the role of a **Data Scientist / Data Analyst** working for a startup investment firm. The task was to extract financial data such as historical share prices and quarterly revenue reports, then visualize them in a dashboard to identify patterns and trends.

Stocks analyzed: **Tesla (TSLA)** and **GameStop (GME)**

---

## 📋 Dataset

- **Stock Data:** Extracted using `yfinance` library (maximum historical period)
- **Tesla Revenue Data:** Web scraped from IBM Skills Network hosted page
- **GameStop Revenue Data:** Web scraped from IBM Skills Network hosted page
- **Data range:** Up to June 2021

---

## 🛠 Technologies Used

- Python, Pandas, NumPy
- Matplotlib
- yfinance
- Requests, BeautifulSoup (Web Scraping)

---

## 📋 Project Modules

1. **Data Extraction** - Extract stock data using yfinance Ticker API
2. **Web Scraping** - Scrape quarterly revenue data using Requests & BeautifulSoup
3. **Data Cleaning** - Remove null values, dollar signs, commas from revenue data
4. **Dashboard Visualization** - Plot historical share price and revenue side by side using Matplotlib

---

## 📈 Key Results

| Stock | Data Source | Period Covered |
|---|---|---|
| Tesla (TSLA) | yfinance + Web Scraping | 2010 – 2021 |
| GameStop (GME) | yfinance + Web Scraping | 2002 – 2021 |

Each dashboard displays:
- Historical Share Price (blue line)
- Historical Quarterly Revenue (green line)

---

## 🏆 Certificate

IBM Data Analysis with Python - Coursera
