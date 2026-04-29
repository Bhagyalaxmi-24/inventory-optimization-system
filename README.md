# Intelligent Inventory Optimization System

##  Project Overview
This project builds an AI-based inventory optimization system using retail sales data.
It helps businesses avoid overstocking and stock shortages by predicting demand and suggesting reorder strategies.
__________________________________________________________________________________________________________________________________________________________________

##  Objectives
* Predict product demand using regression models
* Analyze sales trends and seasonal patterns
* Identify fast and slow-moving products
* Optimize inventory levels
* Generate reorder recommendations
__________________________________________________________________________________________________________________________________________________________________

## Dataset
Retail Sales Dataset (Kaggle) with features:
* Date
* Product Category
* Quantity Sold
* Price per Unit
* Total Amount
__________________________________________________________________________________________________________________________________________________________________

## Methodology

### Data Preprocessing
* Handled missing values using forward fill
* Converted date column to datetime

### Feature Engineering
* Extracted time-based features (month, day, weekday)
* Created lag features (lag_1, lag_7)
* Calculated rolling average demand

### Model Building
* Linear Regression model used
* Train-test split applied
__________________________________________________________________________________________________________________________________________________________________

## 📈 Model Performance
* RMSE Score: ~1.87

__________________________________________________________________________________________________________________________________________________________________

## Inventory Optimization
### Reorder Point Formula
Reorder Point = Average Demand × Lead Time

* Lead time simulated (2–5 days)
* Rolling demand used for realistic estimation

### Stock Decision Logic
* If Inventory ≤ Reorder Point → Reorder Needed
* Else → Stock OK
__________________________________________________________________________________________________________________________________________________________________

## Insights
* Clothing category shows slightly higher demand
* Demand varies over time (seasonality observed)
* System helps reduce stockouts and overstock
__________________________________________________________________________________________________________________________________________________________________

## Tools Used
* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib
_________________________________________________________________________________________________________________________________________________________________

## Author
Bhagyalaxmi Sharnappa Bamungi
