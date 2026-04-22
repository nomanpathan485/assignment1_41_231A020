Data Analytics and Visualization Assignment – 1
CANBK Stock Price Forecasting using
ARIMA
Readme file –
# BSE Stock Price Forecasting using ARIMA
## Student Details
- Name: Noman pathan
- Roll No: 41
- UIN: 231A020
- Stock: CANBK
- Subject: Data Analytics and Visualization
---
## Objective
To analyze CANBK stock daily closing prices for the last 1 year and forecast the
next 30 days closing prices using ARIMA model.
---
## Data Preprocessing
- Converted Date column into datetime format.
- Removed missing values.
- Visualized closing price trend.

- ## Stationarity Test (ADF Test)
- Original closing price series was non-stationary (p-value > 0.05).
- After applying first order differencing (d=1), the series became stationary (pvalue < 0.05).
---
## ARIMA Model
- ACF and PACF plots were used to identify ARIMA parameters.
- ARIMA model was trained and fitted on closing price series.
---
## Forecasting Results
Forecast for next 30 days closing prices was
generated.
Forecast graph was plotted along with historical
data.
---
## Interpretation



- Last Closing Price: [UPDATE AFTER RUNNING: e.g., ₹6500.00]
- Average Forecast Price: [UPDATE AFTER RUNNING: e.g., ₹6550.00]
- Since the forecasted average price is higher than the last closing price,
- CANBK stock is expected to show an upward trend for the next 30
days.
Since the forecasted average price is higher than the last closing price, COFORGE stock is
expected to show an upward trend for the next 30 days.
---
## Files Included
Dataset/CANBK_1year.csv
Dataset/CANBK_forecast_30days.csv
Source_Code/CANBK_ARIMA_Assignment.ipynb
Output_Screenshots folder contains all output graphs and
screenshots.
---

## AI Ethics & Responsible Usage Declaration
This project is created only for academic purposes
AI tools were used only for guidance and understanding
All analysis and coding work was executed and verified by me
No plagiarism or unethical copying was done.
CANBK_ARIMA_Roll21
ARIMA forecasting of CANBK stock for DAV Assignment 1
Repo name: CANBK_ARIMA_Roll21
Download data: NSEIndia.com → Historical → Symbol: BSE → Past 1
year → Save as Dataset/BSE_1year.csv
