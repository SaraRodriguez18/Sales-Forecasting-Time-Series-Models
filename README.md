# Sales Forecasting with Time Series Models
This repository contains a time series forecasting project focused on predicting future sales for an e-commerce retail company. The objective was to estimate the total sales per country for the next month based on historical transactional data.
This project was developed as part of a data science course, with a strong focus on time series analysis, model comparison, and business-oriented insights.

## Project overview
The project is based on a dataset containing daily sales transactions across multiple countries and products.
Each record includes:
- Invoice number  
- Product ID and description  
- Date of transaction  
- Total daily sales  
- Country  

The goal is to analyze historical sales patterns and forecast future demand.

## Objective
The main goals of the project were:
- Analyze sales evolution over time  
- Identify trends, seasonality, and patterns  
- Build forecasting models to predict future sales  
- Compare different time series approaches  
- Provide business insights based on predictions  

## Methodology
The project follows a structured time series analysis workflow:
- Data cleaning and preprocessing  
- Aggregation of sales data by date and country  
- Time series visualization and decomposition (trend, seasonality, residuals)  
- Autocorrelation and partial autocorrelation analysis  
- Model development using different approaches:
  - SARIMAX  
  - Prophet  
  - Boosting-based models  
- Model evaluation and comparison using appropriate metrics  

## Results

The models were evaluated based on their ability to capture temporal patterns and generate accurate forecasts.
- Time series models successfully captured seasonality and trend components  
- Model performance varied depending on the country and data variability  
- Some models showed better generalization for short-term forecasting  

## Best model
The selected model provided the best balance between accuracy and interpretability, effectively capturing both trend and seasonal components of the data.
Key factors influencing performance:
- Proper handling of temporal structure  
- Identification of seasonality patterns  
- Model tuning and parameter selection  

## Main conclusion
The analysis demonstrated that understanding the temporal structure of the data is critical for accurate forecasting.
Models that explicitly account for trend and seasonality outperform more generic approaches, especially in short-term prediction scenarios.
From a business perspective, reliable sales forecasting can support strategic decisions such as inventory planning, investment, and expansion.

## Files

- `Series_Temporales_Sara_Rguez.ipynb` → Full notebook including analysis, modeling, and forecasting  

##  Author

- Sara Rodríguez Portal
