# Store Sales Forecasting Using Historical Data

## Project Overview

This project focuses on predictive analytics using historical retail sales data. The objective is to analyze past sales trends, perform data preprocessing, and build a machine learning model to forecast future sales.

The project uses the Store Sales Time Series Forecasting dataset and applies data analysis, feature engineering, visualization, and regression techniques to predict sales patterns.

---

## Objectives

* Analyze historical sales data
* Clean and preprocess large datasets
* Perform exploratory data analysis (EDA)
* Create meaningful features from date information
* Build a predictive model using Linear Regression
* Evaluate model performance
* Visualize sales trends and predictions

---

## Dataset

Dataset: Store Sales Time Series Forecasting

Files Used:

* train.csv
* stores.csv
* oil.csv
* holidays_events.csv
* transactions.csv

Dataset Features:

* Date
* Store Number
* Product Family
* Sales
* Promotions
* Oil Prices
* Holidays
* Transactions

Target Variable:

* Sales

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Collection

Loaded historical sales data and supporting datasets.

### 2. Data Cleaning

* Checked missing values
* Removed duplicates
* Converted date columns to datetime format

### 3. Feature Engineering

Created additional features:

* Year
* Month
* Day
* Day of Week
* Holiday Indicator

### 4. Exploratory Data Analysis

Generated visualizations to understand:

* Daily Sales Trends
* Monthly Sales Distribution
* Product Category Performance

### 5. Model Building

Implemented Linear Regression for sales prediction.

### 6. Model Evaluation

Performance Metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Visualizations

### Daily Sales Trend

Shows sales growth patterns from 2013 to 2017.

### Monthly Sales Analysis

Identifies months with highest and lowest sales.

### Actual vs Predicted Sales

Compares model predictions with actual sales values.

### Feature Importance

Highlights the impact of features on sales prediction.

---

## Results

The Linear Regression model successfully captured general sales trends and provided future sales predictions.

Evaluation Metrics:

* MAE: 417.69
* RMSE: 928.82
* R² Score: 0.205

---

## Key Insights

* Sales increased significantly between 2013 and 2017.
* Promotions strongly influenced sales performance.
* Holiday periods contributed to higher sales.
* Monthly sales patterns revealed seasonal demand.

---

## Project Structure

store-sales-predictive-analytics/

├── data/
│ ├── train.csv
│ ├── stores.csv
│ ├── oil.csv
│ ├── holidays_events.csv
│ └── transactions.csv
├── notebooks/
│ └── Predictive_Analytics_Using_Historical_Data.ipynb
├── images/
│ ├── daily_sales_trend.png
│ ├── monthly_sales.png
│ ├── actual_vs_predicted.png
│ └── feature_importance.png
└── README.md

---

## Future Improvements

* Implement Random Forest Regressor
* Use XGBoost for better prediction accuracy
* Apply advanced Time Series Forecasting models
* Deploy the model as a web application
* Build an interactive Power BI dashboard

## Dataset

Due to GitHub file size limitations, the dataset is not included in this repository.

Dataset Source:
https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data
