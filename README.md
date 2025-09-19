# API_Data_Pipeline_Currency
This project is a simple Data Pipeline built with Python that automatically fetches currency exchange rates from an open API and exports the results into CSV and Excel files.  It can be extended to work with other APIs (such as weather, news, or stock data).
# 📊 API Data Pipeline (Currency Rates)

## 📌 Description
This project is a simple **Data Pipeline** built with Python that automatically fetches live currency exchange rates from a free public API and exports the results into **CSV** and **Excel** files.  

It’s a beginner-friendly project to demonstrate **Data Engineering basics** such as:
- Collecting data from an API  
- Cleaning & organizing data  
- Saving structured outputs  

---

## ⚙️ Features
- Fetches real-time currency rates (Base: USD).  
- Organizes data into a tabular format.  
- Exports data to:
  - `currency_rates.csv`  
  - `currency_rates.xlsx`  
- Adds a timestamp of when data was collected.  

---

## 🛠️ Requirements
Make sure you have **Python 3.x** installed.  
Install required libraries:  
```bash
pip install requests pandas openpyxl
