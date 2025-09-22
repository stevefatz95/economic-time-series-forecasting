# Forecasting and Modeling Diverse Economic Time Series

This project applies statistical and econometrics-based time series forecasting techniques to real-world datasets from diverse domains, focusing on financial data, macroeconomic indicators and socioeconomic trends. The goal is to analyze, model and forecast time series with varying statistical properties such as trend, volatility and non-stationarity.

---

## Project Overview

The project aims to:

- Assess how different time series models handle diverse statistical properties.  
- Evaluate model limitations in real-world forecasting scenarios.  
- Simulate forecasts and quantify uncertainty using Monte Carlo simulations and Kernel Density Estimation (KDE).  
- Compare model performance across domains and frequencies (daily, monthly, quarterly).  
- Extend analysis using advanced modeling techniques such as ARIMA and ARCH/GARCH.

---

## Datasets

All datasets are stored in the `data` folder:

- `AUD 07042014 2011.csv` – Australian Dollar exchange rate data.  
- `CHF 07042014 2011.csv` – Swiss Franc exchange rate data.  
- `equity_prices_daily.csv` – Daily stock price data. 
- `equity_prices_intraday.csv` – Intraday stock price data. 
- `us_cpi_monthly.csv` – US Consumer Price Index, monthly frequency.  
- `us_gdp_quarterly.csv` – US GDP data, quarterly frequency.

---

## Files Included

- `time-series-forecasting.html` – Static report showcasing methodology, results, and insights.  
- `time-series-forecasting.ipynb` – Jupyter notebook with the full analysis, data preprocessing and modeling workflow.  
- `requirements.txt` – Python dependencies for replicating the analysis.  
- `LICENSE.md` – Project licensing information.

---

## Notebook Structure

The notebook follows a structured workflow:

- **Part 1**: Introduces foundational techniques such as testing for stationarity, applying classical forecasting models, building AR models and performing Monte Carlo simulations with KDE.  
- **Part 2**: Focuses on fitting AR(p) models and generating forward simulations to quantify forecast uncertainty, particularly using higher-frequency datasets.  
- **Part 3**: Explores more advanced methods, including ARIMA and ARCH/GARCH modeling, for deeper insights into time series dynamics.  

The notebook concludes with a discussion that integrates the results, outlines key limitations and proposes potential avenues for future research.

---

## System Requirements

- Python 3.8+  
- OS-independent; analysis was performed on macOS but reproducible on Windows or Linux

---

## How to View the Report

Open `time-series-forecasting.html` in a web browser to explore the methodology, results and insights.
