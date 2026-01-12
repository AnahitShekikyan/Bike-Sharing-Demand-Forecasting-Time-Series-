# Bike-Sharing Demand Forecasting (Time Series) 

This project analyzes bike-sharing rental demand using time series methods in **R** to support operational planning such as bike redistribution, staffing, and maintenance scheduling. The workflow includes data cleaning, exploratory time series analysis, feature engineering, model building, and forecast evaluation.

---

## Project Goals
- Understand demand patterns over time (trend, seasonality, cycles)
- Build forecasting models appropriate for bike-sharing demand
- Evaluate and compare models using standard forecast accuracy metrics

---

## Methods & Models 
**R**
Depending on the final notebook/script version, models may include:
- ETS (Exponential Smoothing)
- ARIMA / Seasonal ARIMA
- Regression with time-series errors (TSLM)
- Holt-Winters
  
**Python**
- Notebook-based modeling workflows
- LSTM models for daily and hourly demand (where included)
- Saved model artifact(s) (for example, .h5)

---

## Results summary
Reported performance from the final report:

| Model | Data resolution | RMSE | MAE | R2 |
|------|------------------|------|-----|----|
| SARIMAX | Daily | 1706.48 | 1237.63 | 0.87 |
| LSTM | Hourly | 46.44 | 30.00 | 0.9554 |
| Linear Regression (baseline) | Hourly | 663.43 | 432.06 | 0.90 |

---

## Tech Stack
R / RStudio
- Common packages:
  - `tidyverse`, `lubridate`, `forecast`, `tsibble`, `fable`, `ggplot2`, `tseries`, `zoo`
  - (Add/remove based on what you used)

Python
- See requirements.txt for the full list of dependencies
---

## Repository Structure (recommended)
.
├── ADS-506 Final Project Initial EDA.Rmd
├── ADS-506-Final-Project-Initial-EDA.html
├── ADS-506-Final-Project-Initial-EDA.pdf
├── ADS_506_Final_Project_Updated.ipynb
├── Update_506_Final_Team_Project.ipynb
├── LSTM_day_data.ipynb
├── LSTM_hour_data.ipynb
├── bike_rentals_lstm_model.h5
├── day.csv
├── hour.csv
├── requirements.txt
├── Bike Sharing Demand Forecasting Using Time Series Models.pdf
└── README.md

---

## Data
- day.csv
- hour.csv

---

## Evaluation
Forecast accuracy may be reported using:
- RMSE
- MAE
- optional: MAPE, sMAPE, MASE

---

## Deliverables
- Bike Sharing Demand Forecasting Using Time Series Models.pdf
- ADS-506-Final-Project-Initial-EDA.pdf / .html
- RMarkdown analysis (Rmd)
- Python notebooks and saved model artifact (.h5)
