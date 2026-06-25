\# Sales Forecasting Using Machine Learning



\## Project Overview



This project develops a machine learning-based sales forecasting system to predict future sales using historical sales data. The model identifies sales patterns, seasonality, trends, and lag-based relationships to generate accurate future sales predictions.



The project also includes Tableau dashboards and data visualizations to help businesses understand sales performance and forecast future demand.



\---



\## Objectives



\- Analyze historical sales data

\- Build a forecasting model

\- Predict future sales

\- Visualize sales trends and forecasts

\- Support business planning and decision-making



\---



\## Tech Stack



\- Python

\- Pandas

\- NumPy

\- Scikit-Learn

\- lightgbm

\- Matplotlib

\- Seaborn

\- joblib

\- Tableau



\---



\## Files

Sample - Superstore.csv : Input file

\---



\## Project Structure



FUTURE\_ML\_01/



├── data/



├── notebook/



├── plots/



├── tableau\_dashboard/



├── README.md



└── requirements.txt



\---



\## Features Used



\### Calendar Features

\- Year

\- Month

\- Day

\- Day of Week

\- Quarter

\- Time Index



\### Lag Features

\- Lag\_1

\- Lag\_7

\- Lag\_14

\- Lag\_30



\### Rolling Statistics Features

\- Rolling\_14

\- Lag\_7\_Rolling\_Mean

\- Lag\_14\_Rolling\_Std

\- Expanding Mean



\### Sales Aggregation Features

\- Average Weekly Sales

\- Quantity

\- Quantity × Average Weekly Sales



\### Seasonal Features

\- Season



\### Cyclical Date Features

\- Month Sin

\- Month Cos

\- Day of Week Sin

\- Day of Week Cos

\---



\## Visualizations



\### Matplotlib Visualizations



\- actual\_vs\_predicted\_sales

\- Average Sales by Season

\- daily\_sales

\- feature\_correlation

\- feature\_importance

\- monthly\_sales

\- residual\_plot

\- sales\_by\_category

\- sales\_by\_region

\- sales\_forecast

\- sales\_forecast\_chart

\- sales\_forecast\_residual

\- sales\_forecast\_residual\_7\_days

\---



\### Tableau Dashboards



\- Sales Forecasting

\- Sales history dashboard

\- Sales Regression

\---



\## Forecast Interpretation



The forecasting model predicts future sales based on historical sales patterns and seasonal trends.



Businesses can use these forecasts for:



\- Inventory planning

\- Resource allocation

\- Revenue forecasting

\- Marketing campaign planning

\- Supply chain optimization



\---



\## Business Impact



This solution enables businesses to make proactive decisions by anticipating future demand instead of reacting to changes after they occur.



Benefits include:



\- Reduced stock shortages

\- Better inventory management

\- Improved budgeting

\- More efficient operations

\- Data-driven decision making



\---



\## Model Output



The model generates future sales predictions that can be used to estimate demand for upcoming days and support business planning activities.



\---



\## How to Run





1\. Install dependencies



pip install -r requirements.txt



2\. Open the notebook



\- task\_1\_feat\_engg.ipynb

\- task\_1\_prediction.ipynb

\- task 1 train\_test.ipynb



3\. Run all cells to reproduce results



\---



\## Dashboard Preview



!\[Sales history dashboard](tableau\_dashboard/Sales history dashboard.png)



!\[Sales Regression](tableau\_dashboard/Sales Regression.png)



!\[Sales Forecasting](tableau\_dashboard/Sales Forecasting.png)



\## To install requirements



pip install -r requirements.txt



\---



\## Author



OVIYAA A J



Future Interns - Machine Learning Track

