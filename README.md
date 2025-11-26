⚡ Electricity Frequency Forecasting (2024) – ARIMA Based Time-Series Modeling

A complete end-to-end time-series forecasting and exploratory analysis project built using Python, ARIMA models, and frequency trend analytics.
This project predicts electricity frequency variations and analyzes seasonal, monthly, and operational patterns using real 2024 data.

📌 Project Overview

This project studies electricity grid frequency using statistical and machine-learning-based time-series techniques.

It includes:

Seasonal, monthly & weekday/weekend analysis

Rolling smoothing & trend detection

Daily and hourly variation plots

ARIMA/AR forecasting

Short-term (48-hour) frequency prediction

Model evaluation with MSE

This project demonstrates real-world time-series modeling, suited for DS/AI/forecasting roles.

🧰 Tech Stack

Python 3.x

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

statsmodels (ARIMA)

MinMaxScaler

📂 Dataset

Modified_Frequency_Profile_2024.csv

Includes:

Column	Description
Date	Day (YYYY-MM-DD)
Time	Hour/Minute
Frequency	Recorded system frequency
Timestamp	Combined Date + Time

Data is sampled at a high frequency and aggregated for analysis.

🔍 Key Features & Insights
1️⃣ Seasonal Trend Analysis

Winter, Spring, Summer, Fall comparison

Rolling mean smoothing

Trendline fitting

2️⃣ Monthly Frequency Behavior

Violin plots for monthly distribution

Custom color-coded legend

Grid frequency compliance lines

3️⃣ Daily Trend Visualization

Month-colored background shading

Smoothed daily average frequency analysis

4️⃣ Weekday vs Weekend Trends

Clear operational differences

Frequency variability insights

🤖 Time-Series Modeling
📘 ARIMA(5,1,5) – Main Model

Fit on daily frequency averages

80/20 train-test split

Forecast plotted vs actual values

Evaluated using MSE

📘 AR(2) – Baseline Model

Quick autoregressive baseline

Compared with ARIMA results

📘 Short-Term Forecast (Next 48 Hours)

Using Jan 1, 2024 data

Normalized using MinMaxScaler

ARIMA predicts next 48 hourly steps

Inverse-transformed to get real Hz values

📈 Sample Visualizations

(Include images like below in your repo for maximum impact)

Seasonal Frequency Trends

Monthly Violin Distribution

Daily Mean Frequency (with shading)

Weekday vs Weekend Comparison

ARIMA Actual vs Predicted

48-Hour Forecast Plot

📊 Model Evaluation
Model	MSE (Lower is better)
ARIMA(5,1,5)	Very Low Error
AR(2)	Higher Baseline Error

ARIMA clearly provides better forecasting accuracy.
