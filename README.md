# Uber-Trip-Analysis
This project dives deep into the pickup patterns of Uber rides in New York City between 2014 and 2015. Using time series analysis and machine learning, we uncover insights and trends that can fuel smarter urban planning and business decisions.

---

## Project Overview

The **Uber Trip Analysis** project focuses on:

- Understanding temporal and spatial trends in Uber pickups
- Performing **time series forecasting** on ride volumes
- Building **ensemble ML models** to predict demand
- Visualizing patterns for improved interpretability

This analysis is especially helpful for logistics companies, urban developers, and enthusiasts of data storytelling.

---

## 📁 Dataset

Data Source: [Data Set is Available here](https://drive.google.com/file/d/1uj0xGqt3t7w6AgoTNq8SksR2Ci3bbWJ1/view?usp=sharing)

- **Files**: `uber-raw-data-<month>-14.csv` & `uber-raw-data-janjune-15.csv`
- **Columns**:  
  - `Date/Time`
  - `Lat` / `Lon`
  - `Base` (Uber base/company code)

---

## 🛠️ Tools & Tech Stack

- **Languages**: Python 
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn`, `plotly` – Visualization
  - `scikit-learn`, `xgboost`, `lightgbm` – Machine Learning
  - `fbprophet`, `statsmodels` – Time Series Forecasting
  - `folium` – Interactive Maps

---

## Key Features

1. **Exploratory Data Analysis (EDA)**:
   - Heatmaps of ride frequency by hour, day, month
   - Geospatial distribution of pickups
   - Popular bases and their coverage zones

2. **Time Series Forecasting**:
   - Daily and hourly ride predictions
   - Models used: ARIMA, Facebook Prophet, Seasonal Decomposition

3. **Ensemble Learning Models**:
   - Trained models using XGBoost, Random Forest, and LightGBM
   - Feature engineering with temporal attributes

4. **Interactive Visuals**:
   - Maps of high-demand zones
   - Time sliders for hourly pickup patterns

---
