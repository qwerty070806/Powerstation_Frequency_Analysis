# ⚡ PowerstationDAV – Frequency Stability Analysis

A Python-based data analysis and forecasting project focused on studying the stability of electric grid frequency using time-series techniques. The dataset is sourced from the [NERLDC (North Eastern Regional Load Despatch Centre)](https://www.nerldc.in/), and the project provides visual and statistical insights into frequency behavior, anomalies, and predictions.

---

## 📊 Features

- ✅ Cleaned and merged raw CSV data with separate Date and Time columns into a unified datetime format
- 📈 Visualized grid frequency trends over time using:
  - Heatmaps (hour vs day patterns)
  - Boxplots (weekday vs weekend frequency patterns)
  - Histograms with KDE (frequency distributions)
- ⚠️ Detected and categorized violations (underfrequency, overfrequency, stable) using thresholding
- 📅 Compared frequency behavior between weekdays and weekends
- 📉 Implemented ARIMA and SARIMAX models for frequency forecasting
- 📊 Evaluated forecasting models using RMSE and visual residual analysis
