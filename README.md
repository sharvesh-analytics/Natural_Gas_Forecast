# Natural Gas Price Forecasting & Interpolation 📉🔥

This project is a part of the **JPMorgan Chase & Co. Virtual Internship Program** on Forage. The goal is to analyze historical natural gas price data, estimate monthly prices within the historical range (Interpolation), and predict/forecast future prices up to one year ahead (Extrapolation) using Machine Learning.

---

## 🚀 Project Overview

The project utilizes a time-series dataset containing monthly snapshot prices of natural gas from **October 31, 2020, to September 30, 2024**. 

Downstream operators use storage as a buffer against supply chain disruptions. This tool helps financial analysts and clients estimate indicative pricing for longer-term storage contracts by predicting pricing trends.

### Key Features:

* **Data Visualization:** Line plots to observe seasonal trends and price fluctuations.
* **Intelligent Interpolation:** Uses `numpy.interp` to accurately estimate historical prices on any specific dates between 2020 and 2024.
* **Machine Learning Extrapolation:** Implements a `LinearRegression` model from `scikit-learn` to forecast natural gas prices 1 year into the future (up to late 2025).

---

## 📁 Dataset Details

The dataset consists of a CSV file with two primary columns:
1. `Dates`: Monthly snapshot dates (MM/DD/YY).
2. `Prices`: Historical market price of natural gas delivered at the end of each calendar month (stored in scientific/numeric format).

---

## 🛠️ Tech Stack & Libraries Used

* **Python 3**
* **Pandas:** For data manipulation and CSV handling.
* **NumPy:** For mathematical calculations and linear interpolation.
* **Matplotlib:** For data visualization and trends plotting.
* **Scikit-Learn:** For training the Linear Regression model.

---
## AUTHOR*
  SHARVESH PANDEY
