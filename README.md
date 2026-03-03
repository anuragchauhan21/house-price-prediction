# California House Price Prediction

## Overview

This project predicts the **median house value** in California using information such as income level, housing age, population, and location.

The goal is to build a machine learning model that can estimate house prices accurately and help buyers, sellers, and policymakers make better real estate decisions.

Dataset used: [California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Approach & Tech Stack

> Data Cleaning → Exploratory Analysis → Model Building → Evaluation → Insights

- Python (Pandas, NumPy)
- Data Visualization (Matplotlib)
- Machine Learning (Scikit-learn)
- Models Used:
  - Linear Regression
  - Random Forest Regressor

## Model Performance

Two models were compared:

### Linear Regression
- RMSE: 66,696

### Random Forest
- RMSE: 50,772
- Cross Validation Score (Average R²): 0.80

Random Forest performed better and provided more accurate predictions.

## Key Insights

- Income level is the most important factor affecting house prices.
- The final model explains about 80% of price variation.
- House prices depend on multiple factors working together, not just one (mojorly median_income).
- Tree-based models handle complex relationships better than simple linear models.

## Business Impact

This model can help:

- Real estate companies estimate property prices more accurately.
- Buyers understand fair market value.
- Policymakers study housing trends.
- Financial institutions assess property-related risk.

Project by [**Anurag Chauhan**](https://www.linkedin.com/in/theanuragchauhan/)
