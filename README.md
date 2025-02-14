# Time-Series-ARIMA-
# Time Series Forecasting of Harvard University Yearly Costs

This repository showcases a time series forecasting project using an ARIMA-based approach to predict Harvard University’s yearly total expenses (tuition, fees, etc.). The analysis spans 1985–2016 and forecasts 2017–2023, comparing predicted costs with real data.

## Repository Contents

1. **Report (PDF/HTML)**  
   A detailed explanation of the steps taken to prepare, analyze, and interpret the ARIMA model forecasts. It includes data preprocessing, differencing, model selection, and forecasting performance.

2. **R Markdown Notebook (.Rmd)**  
   Contains R code for reading in the dataset, exploring stationarity, fitting ARIMA models, comparing actual vs. forecasted values, and visualizing results.

3. **Dataset (harvard_fees.csv)**  
   Holds the yearly total expenses from 1985–2016. This dataset is used directly by the R script or R Markdown to shape the time series and build the ARIMA model.

4. **Generated Plots**  
   - Time series plots of the original data, differenced data, ACF/PACF plots, and forecast vs. actual cost comparisons.
   - PNG outputs typically named according to the ARIMA parameters used.

## Getting Started

1. **Clone the Repository**  
   ```bash
   gh repo clone RCH98/Time-Series-ARIMA-
