# Supermart Grocery Sales Analysis & Prediction

## Overview
This project performs a comprehensive data analysis of the Supermart Grocery Sales dataset to understand sales trends, top-performing products, and key markets. Additionally, it implements a **Machine Learning model** to forecast sales based on various features.

## Dataset
The dataset contains retail analytics data for a grocery supermarket, including information on:
- **Orders**: ID, Date, Region, State, City
- **Customers**: Name
- **Products**: Category, Sub Category
- **Financials**: Sales, Discount, Profit

## Features

### 1. Exploratory Data Analysis (EDA)
The notebook analyses:
- **Top 5 Cities**: Identifying the most profitable geographic locations.
- **Monthly Sales Trends**: Visualizing sales performance over time to spot seasonality.
- **Category Performance**: Breaking down sales by product category to find top sellers.

### 2. Machine Learning: Sales Prediction
A **Random Forest Regressor** model has been implemented to predict sales.
- **Features Used**: Category, Sub Category, City, Region, State, and Date features (Year, Month, Day).
- **Metric**: The model's performance is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Visualizations
The project generates several insights and visualizations, such as:
- Bar charts for Top Cities and Categories.
- Line charts for Sales Trends.
- Scatter plot for Actual vs. Predicted Sales (ML).

## Prerequisities
Ensure you have the following Python libraries installed:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

## How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```
2. Run all cells to execute the analysis and train the ML model.

## Results
The analysis provides actionable insights for inventory management and marketing strategies, while the ML model offers a predictive tool for future sales estimation.
