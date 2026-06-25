# FUTURE_ML_01
Sales &amp; Demand Forecasting for Businesses
# Sales Forecasting Using Machine Learning

## Project Overview

This project develops a machine learning-based sales forecasting system to predict future sales using historical sales data. The model identifies sales patterns, seasonality, trends, and lag-based relationships to generate accurate future sales predictions.

The project also includes Tableau dashboards and data visualizations to help businesses understand sales performance and forecast future demand.

---

## Objectives

- Analyze historical sales data
- Build a forecasting model
- Predict future sales
- Visualize sales trends and forecasts
- Support business planning and decision-making

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- lightgbm
- Matplotlib
- Seaborn
- joblib
- Tableau

---

## Files 
Sample - Superstore.csv : Input file 
---

## Project Structure

FUTURE_ML_01/

├── data/

├── notebook/

├── plots/

├── tableau_dashboard/

├── README.md

└── requirements.txt

---

## Features Used

### Calendar Features
- Year
- Month
- Day
- Day of Week
- Quarter
- Time Index

### Lag Features
- Lag_1
- Lag_7
- Lag_14
- Lag_30

### Rolling Statistics Features
- Rolling_14
- Lag_7_Rolling_Mean
- Lag_14_Rolling_Std
- Expanding Mean

### Sales Aggregation Features
- Average Weekly Sales
- Quantity
- Quantity × Average Weekly Sales

### Seasonal Features
- Season

### Cyclical Date Features
- Month Sin
- Month Cos
- Day of Week Sin
- Day of Week Cos
---

## Visualizations

### Matplotlib Visualizations

- actual_vs_predicted_sales  
- Average Sales by Season  
- daily_sales  
- feature_correlation  
- feature_importance  
- monthly_sales  
- residual_plot  
- sales_by_category  
- sales_by_region  
- sales_forecast  
- sales_forecast_chart  
- sales_forecast_residual  
- sales_forecast_residual_7_days
---

### Tableau Dashboards

- Sales Forecasting  
- Sales history dashboard    
- Sales Regression  
---

## Forecast Interpretation

The forecasting model predicts future sales based on historical sales patterns and seasonal trends.

Businesses can use these forecasts for:

- Inventory planning
- Resource allocation
- Revenue forecasting
- Marketing campaign planning
- Supply chain optimization

---

## Business Impact

This solution enables businesses to make proactive decisions by anticipating future demand instead of reacting to changes after they occur.

Benefits include:

- Reduced stock shortages
- Better inventory management
- Improved budgeting
- More efficient operations
- Data-driven decision making

---

## Model Output

The model generates future sales predictions that can be used to estimate demand for upcoming days and support business planning activities.

---

## How to Run

1. Clone the repository

git clone <repository-link>

2. Install dependencies

pip install -r requirements.txt

3. Open the notebook

- task_1_feat_engg.ipynb  
- task_1_prediction.ipynb  
- task 1 train_test.ipynb

4. Run all cells to reproduce results

---

## To install requirements

pip install -r requirements.txt

---

## Author

OVIYAA A J

Future Interns - Machine Learning Track
