# Task 2 – Real Estate Housing Price Prediction

## Project Overview
This project focuses on predicting median house values using the California Housing dataset and Machine Learning regression algorithms.

## Objectives
- Perform Exploratory Data Analysis (EDA).
- Handle missing values.
- Perform feature engineering.
- Apply feature scaling and categorical encoding.
- Train and compare regression models.
- Evaluate models using RMSE, MAE, and R².

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-Learn
- Jupyter Notebook

## Machine Learning Models
1. Ordinary Least Squares (OLS) Regression
2. Ridge Regression (L2)
3. Lasso Regression (L1)

## Model Performance

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| OLS | 68917.32 | 49709.54 | 0.6375 |
| Ridge | 68925.96 | 49715.84 | 0.6375 |
| Lasso | 68918.68 | 49710.27 | 0.6375 |

## Best Model
OLS Regression achieved the lowest RMSE and MAE among the three models.

## Project Files
- `Task_2_Housing_Price_Prediction.ipynb` – Complete implementation and analysis.

## Conclusion
The project demonstrates an end-to-end regression workflow, including data preprocessing, feature engineering, hyperparameter tuning, model evaluation, and residual analysis.
