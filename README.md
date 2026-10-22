Retail Demand Forecasting System

Overview
This project builds an end-to-end retail demand forecasting solution using Machine Learning and Time Series Forecasting techniques. The goal is to predict future product demand based on historical sales data and support inventory optimization, demand planning, and business decision-making.

Business Problem
Retail businesses often struggle with stock-outs and overstocking due to inaccurate demand estimation. This project helps forecast future sales demand, identify seasonal trends, and improve inventory planning.

Objectives
• Forecast future product demand
• Analyze seasonal sales patterns
• Compare Prophet and XGBoost forecasting models
• Generate insights for inventory optimization
• Visualize sales trends and forecasted demand

Technology Stack
• Python
• Pandas
• NumPy
• Scikit-Learn
• XGBoost
• Prophet
• Matplotlib
• Seaborn
• Joblib

Project Workflow

1. Data Collection
   - Historical retail sales data
   - Product-level sales records
   - Time-based sales information

2. Data Preprocessing
   - Missing value handling
   - Date conversion
   - Data cleaning

3. Feature Engineering
   - Year
   - Month
   - Quarter
   - Day of Week
   - Lag Features
   - Rolling Mean Features

4. Model Development
   - Prophet Forecasting Model
   - XGBoost Regression Model

5. Model Evaluation
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

6. Forecast Visualization
   - Actual vs Predicted Sales
   - Trend Analysis
   - Demand Forecast Charts

Key Features
• Automated Feature Engineering
• Demand Forecasting
• Sales Trend Analysis
• Inventory Planning Insights
• Forecast Visualization
• Model Persistence

Results
• Improved forecasting accuracy through feature engineering
• Identified seasonal demand patterns
• Supported inventory optimization decisions
• Generated business insights from retail sales data

Repository Structure

Retail-Demand-Forecasting-System

data/
    retail_sales.csv

models/
    xgb_model.pkl
    prophet_model.pkl

src/
    data_loader.py
    feature_engineering.py
    train_xgboost.py
    train_prophet.py
    evaluate.py
    visualize.py

outputs/
    xgb_forecast.png
    prophet_forecast.png

requirements.txt
main.py
README.md

Future Enhancements
• MLflow Experiment Tracking
• AWS Deployment
• Streamlit Dashboard
• Real-Time Forecast API
• Automated Retraining Pipeline

Author
Shweta Kumari

Skills Demonstrated
Python | SQL | Machine Learning | XGBoost | Prophet | Time Series Forecasting | Feature Engineering | Data Analysis | Forecasting | Predictive Analytics
