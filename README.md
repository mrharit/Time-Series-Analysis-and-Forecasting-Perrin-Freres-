
# 🥂 Champagne Sales Time Series Forecasting

This project performs end-to-end time series analysis on **Perrin Freres' monthly champagne sales data (1964–1972)**. The goal is to understand the historical sales patterns and forecast future demand using classical statistical methods.

---

## 📁 Dataset

- **File**: `perrin-freres-monthly-champagne-.csv`
- **Source**: Historic monthly champagne sales (in millions)
- **Duration**: Jan 1964 to Sep 1972
- **Columns**:
  - `Month`: Date in `YYYY-MM` format
  - `Sales`: Champagne sales in millions

---

## 🧰 Tech Stack

- **Language**: Python (Jupyter Notebook)
- **Libraries**:
  - `pandas` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization
  - `statsmodels` – Decomposition & forecasting
  - `scikit-learn` (optional, if regression/ML used)
  - `Prophet` or `ARIMA` (if applicable)

---

## 🔍 Key Steps

### 1. Data Cleaning & Preparation
- Converted `Month` column to datetime format
- Removed invalid rows (e.g., column header inside data)
- Verified missing values and corrected data types

### 2. Exploratory Data Analysis (EDA)
- Line plot of monthly sales over time
- Seasonal patterns observed (e.g., peak in December)
- Rolling mean/smoothing to identify trends

### 3. Time Series Decomposition
- Used `seasonal_decompose` to break data into:
  - **Trend**
  - **Seasonality**
  - **Residuals**

### 4. Forecasting
- Modelled future sales using statistical methods such as:
  - **ARIMA/SARIMA**
  - (Optional) Facebook Prophet or Holt-Winters Exponential Smoothing
- Trained model and validated on test data

### 5. Visualization
- Plotted:
  - Actual vs Predicted Sales
  - Confidence Intervals
  - Forecasted Trends

---

## 📈 Output

- 📊 Clear insights into seasonal patterns (e.g., December sales surge)
- 📉 Forecasting up to `n` months into the future
- 🎯 Improved understanding of champagne sales dynamics over time

---

## 🎯 Real-World Application

Such analysis is crucial for:
- **Retail & Inventory Planning** for seasonal demand
- **Sales Forecasting** to set monthly targets
- **Marketing Strategy** optimization

---

## 🤝 Author

Made with 📊 by [mrharit](https://github.com/mrharit)  
*For questions or collaborations, feel free to reach out!*
