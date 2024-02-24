# Inventory Management Using Time Series Analysis and Forecasting 📊🕒

Managing the inventory of spare parts in various service centers to meet market demand poses a significant challenge. Despite substantial investments in spare parts inventory, ensuring the availability of these parts remains a problematic area. In this project, I've tackled this issue by employing time series analysis techniques 🧮🔍.

## Project Overview 📝
The goal of this project is to optimize inventory levels 📦 in service centers by accurately forecasting demand for spare parts. This approach not only aims to reduce inventory costs but also to improve spare parts availability, thereby enhancing customer satisfaction 🌟.

## Contents 📚
- **[Import Stuff](#import-stuff)**: Setting up the necessary libraries and tools.
- **[Load the Data](#load-the-data)**: Loading the dataset for analysis.
- **[Basic EDA](#basic-eda)**: Conducting initial exploratory data analysis to understand the dataset.
- **[Data Preprocessing](#data-preprocessing)**: Cleaning and preparing the data for time series analysis.
- **[Advanced EDA](#advanced-eda)**: Diving deeper into the data to uncover patterns and insights.
- **[Time Series Analysis](#time-series-analysis)**: Analyzing the data to identify trends, seasonality, and other components.
- **[Time Series Forecasting](#time-series-forecasting)**: Predicting future demand for spare parts using various time series models.
- **[Model Evaluation](#models-evaluation)**: Assessing the performance of deployed models.
- **[Multivariate Analysis](#induct-exogenous-variable-in-sarimax-model)**: Enhancing the SARIMAX model by incorporating additional variables.

## Features in Data 🔍
The dataset includes the following features, which are crucial for analysis and forecasting:
- `invoice_date`
- `job_card_date`
- `business_partner_name`
- `vehicle_no`
- `vehicle_model`
- `current_km_reading`
- `invoice_line_text`

## Models Deployed 🤖
To address the forecasting challenge, the following models were deployed:
- **Auto Regression (AR)**
- **Moving Average (MA)**
- **Exponential Weighted Moving Average (EWMA)**
- **Holt-Winters Method**
- **Seasonal Autoregressive Integrated Moving Average (SARIMA)**
- **Seasonal Autoregressive Integrated Moving Average with Exogenous variables (SARIMAX)**

## Model Evaluation 📏
The models were evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**

This project demonstrates the power of time series analysis and forecasting in solving real-world inventory management challenges. By predicting demand more accurately, service centers can optimize their inventory levels, reduce costs, and ensure the availability of spare parts, ultimately leading to greater customer satisfaction.
