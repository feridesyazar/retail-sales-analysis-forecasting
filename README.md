# 📊 Retail Sales Analysis & Forecasting

## Project Overview

This project analyzes monthly retail and warehouse sales data from Montgomery County, Maryland. It explores sales trends, product categories, and seasonal patterns, then compares two regression models for predicting recorded monthly retail sales volumes.

## Dataset

**Source:** [Warehouse and Retail Sales – Montgomery County, Maryland (Data.gov)](https://catalog.data.gov/dataset/warehouse-and-retail-sales)

The dataset reports sales volumes in **cases**, not revenue. In the analyzed data, only **27 months** have recorded sales between June 2017 and August 2026; **84 calendar months** are missing. Missing months are not treated as zero sales.

## Tools and Methods

- Python, Pandas, Matplotlib, Scikit-learn
- Data cleaning and Exploratory Data Analysis (EDA)
- Retail and warehouse sales trends
- Product category and calendar-month analysis
- Feature engineering using year and month
- Chronological train/test split
- Linear Regression and Decision Tree Regression
- Model evaluation using MAE, RMSE, and R²

## Key Findings

- **LIQUOR** had the highest retail sales volume among the product categories.
- **Linear Regression** achieved a lower test MAE (9,943.35 cases) than Decision Tree Regression (17,029.96 cases).
- The six test observations come from 2020 and 2026 rather than six consecutive months.

## Limitations

The dataset contains major time gaps, especially between 2021 and 2025. The models use only calendar year and month as features. Therefore, the results demonstrate regression modeling but should not be considered reliable future sales forecasts.
