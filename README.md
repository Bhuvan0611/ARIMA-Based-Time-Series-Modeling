# ⚡ Electricity Frequency Forecasting (2024)
### *ARIMA-Based Time-Series Modeling & Grid Stability Analysis*

A complete end-to-end **time-series forecasting** and **exploratory analysis** project built using Python, ARIMA models, and grid-frequency analytics.  
This project predicts **electricity frequency variations** and analyzes seasonal, monthly, and operational patterns using real 2024 system frequency data.

---

## 📌 Project Overview

This project focuses on **electricity grid frequency stability**, applying statistical and ML-based time-series techniques.

Key components:

- Seasonal, monthly & weekday/weekend analysis  
- Rolling smoothing & trend extraction  
- Daily and hourly variation visualization  
- ARIMA/AR forecasting  
- Short-term (48-hour) prediction  
- Model evaluation via MSE  

This project demonstrates **real-world forecasting**, suitable for DS/AI/Energy Analytics profiles.

---

## 🧰 Tech Stack

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- statsmodels (ARIMA)  
- MinMaxScaler  

---

## 📂 Dataset

**File:** `Modified_Frequency_Profile_2024.csv`

| Column     | Description               |
|------------|---------------------------|
| Date       | Day (YYYY-MM-DD)          |
| Time       | Timestamp of measurement  |
| Frequency  | System frequency (Hz)     |
| Timestamp  | Combined Date + Time      |

Data is sampled at high frequency and aggregated for analysis.

---

## 🔍 Key Features & Insights

### 1️⃣ Seasonal Trend Analysis
- Seasonal segmentation (Winter, Spring, Summer, Fall)  
- Rolling mean smoothing  
- Trendline fitting  

### 2️⃣ Monthly Frequency Behavior
- Violin plots  
- Color-coded month mapping  
- Grid compliance markers  

### 3️⃣ Daily Trend Visualization
- Month-wise shaded background  
- Daily mean frequency tracking  

### 4️⃣ Weekday vs Weekend Trends
- Operational behavior differences  
- Frequency stability comparison  

---

## 🤖 Time-Series Modeling

### 📘 ARIMA(5,1,5) – Main Model
- Fit on daily resampled frequency  
- 80/20 train-test split  
- Forecast plotted against real values  
- Evaluated using **Mean Squared Error (MSE)**  

### 📘 AR(2) – Baseline Model
- Simple autoregressive benchmark  
- Compared with ARIMA performance  

### 📘 Short-Term Forecast (Next 48 Hours)
- Based on Jan 1, 2024 hourly data  
- Scaled using MinMaxScaler  
- ARIMA predicts next 48 hourly steps  
- Inverse transformation applied  

---

## 📈 Sample Visualizations
*(Add images in your GitHub repo)*

- Seasonal Frequency Trends  
- Monthly Violin Distribution  
- Daily Mean Frequency (with month shading)  
- Weekday vs Weekend Comparison  
- ARIMA Actual vs Predicted  
- 48-Hour Forecast Plot  

---

## 📊 Model Evaluation

| Model         | MSE (Lower = Better) |
|---------------|------------------------|
| ARIMA(5,1,5)  | Very Low Error         |
| AR(2)         | Higher Baseline Error  |

ARIMA clearly outperforms the baseline AR model.

---

## 🚀 Future Improvements

- Auto-ARIMA / SARIMA  
- LSTM/GRU neural models  
- Residual diagnostics (ACF/PACF)  
- Deployment using FastAPI  
- Streamlit-based dashboard  

---

## 👨‍💻 Developed By

**Venkata Bhuvan Kosuru**  
IIT Patna — AI & Data Science  

---

## ⭐ Star the repo if you found it useful!
