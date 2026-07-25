# Tesla & GameStop Stock vs. Revenue Analysis

A Python-based financial data extraction and visualization project. This project pulls historical stock data using `yfinance` and web-scrapes quarterly revenue data using `BeautifulSoup` and `pandas` to visualize company performance over time.

---

## 📌 Project Overview
This project analyzes the historical relationship between share prices and quarterly revenue for **Tesla (TSLA)** and **GameStop (GME)**. 

* **Stock Data Source:** Yahoo Finance API (`yfinance`)
* **Revenue Data Source:** Web-scraped HTML tables (`requests`, `BeautifulSoup`, `pandas.read_html`)
* **Visualization:** Matplotlib dual-plot graphs showing price trends vs. revenue performance

---

## 🛠️ Tech Stack & Dependencies
* **Python 3.x**
* **Data Extraction & Manipulation:** `yfinance`, `pandas`, `requests`, `BeautifulSoup4`
* **Data Visualization:** `matplotlib`

---

## 📊 Features & Workflow
1. **Historical Price Extraction:** Pulls maximum available history for TSLA and GME using `yfinance`.
2. **Web Scraping:** Parses web tables to extract clean revenue data and normalizes currency formats.
3. **Data Cleaning:** Removes invalid values, handles missing data, and formats timestamps.
4. **Visualization:** Generates side-by-side subplots comparing share prices with quarterly revenues.
