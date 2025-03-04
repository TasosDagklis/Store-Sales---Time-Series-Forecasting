# Store-Sales-Time-Series-Forecasting
Store Sales - Time Series Forecasting
This repository contains a solution for the Kaggle competition **"Store Sales - Time Series Forecasting"**, where the goal is to predict unit sales for thousands of items across multiple stores of Corporación Favorita, a major grocery retailer in Ecuador.

## 📌 Project Overview

In this competition, we apply **time-series forecasting** techniques to predict store sales based on historical data. The dataset includes **transaction records**, **store and item metadata**, and **promotion information**, making it an excellent opportunity to practice and refine **machine learning** skills in demand forecasting.

## 🚀 Approach

The project follows a structured pipeline:

1. **Data Preprocessing**  
   - Handling missing values, outliers, and inconsistencies  
   - Feature engineering (e.g. extracting temporal features, encoding categorical variables)  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing sales trends, seasonality, and promotional impacts  
   - Identifying correlations between variables  

3. **Model Selection & Training**    
   - Using advanced machine learning approaches (XGBoost)  
   - Hyperparameter tuning and model evaluation  

4. **Forecasting & Submission**  
   - Generating predictions for future sales  
   - Evaluating performance using **Root Mean Squared Logarithmic Error (RMSLE)**  

## 📊 Dataset

The dataset includes:
- **train.csv**: Historical sales data with store and item information  
- **test.csv**: Data to generate forecasts for  
- **stores.csv**: Metadata about each store (location, type, etc.)  
- **transactions.csv**: Aggregated daily transactions per store  
- **oil.csv**: Ecuadorian oil prices (economic indicator)  
- **holidays_events.csv**: National and regional holiday information
