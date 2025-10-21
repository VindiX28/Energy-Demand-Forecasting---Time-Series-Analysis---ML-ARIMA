# Energy-Demand-Forecasting---Time-Series-Analysis---ML-ARIMA

🌞 Time Series Analysis and Forecasting with ARIMA
This project focuses on time series analysis and forecasting of Italy’s electric load and solar generation data for the year 2016 using the ARIMA (AutoRegressive Integrated Moving Average) model.

📊 Project Overview

The goal of this analysis is to:

Explore and visualize trends in solar generation and electric load over time.
Check for stationarity in the time series using the Augmented Dickey-Fuller (ADF) test.
Build and evaluate ARIMA models for both datasets.
Assess model performance using Root Mean Squared Error (RMSE) and visualize actual vs. predicted values.

🧠 Key Steps

Data Loading & Cleaning
Handle missing values using forward-fill (ffill).
Convert timestamps to proper datetime format.
Exploratory Data Analysis (EDA)
Visualize trends for IT_load_new and IT_solar_generation.
Observe cyclical and seasonal patterns.
Stationarity Testing
Conducted ADF tests to verify stationarity for both series.
Model Building
Identified suitable parameters (p, d, q) using ACF and PACF plots.
Trained multiple ARIMA models and compared their RMSE values.
Forecasting & Evaluation
Compared actual vs predicted values using line plots.

Achieved:
RMSE ≈ 7715 for Load
RMSE ≈ 2486 for Solar Generation

🧩 Tools & Libraries

Python : Pandas, NumPy, Matplotlib, Statsmodels, Scikit-learn

📈 Results
The ARIMA models effectively captured the overall trends in both the load and solar generation data. While minor deviations exist, the models demonstrate strong predictive capabilities for short-term forecasting.
