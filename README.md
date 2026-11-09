# Sales Prediction Using Python

## Project Overview
This project predicts product sales based on advertising budgets spent on TV, Radio, and Newspaper using Machine Learning.

## Dataset
- Dataset: Advertising.csv
- Total Records: 200
- Features: TV, Radio, Newspaper
- Target: Sales

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models
1. Linear Regression
2. Random Forest Regressor

## Model Performance

| Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 1.46 | 0.62 |
| RMSE | 1.78 | 0.77 |
| R² Score | 89.94% | 98.13% |

## Feature Importance
- TV: 62.48%
- Radio: 36.22%
- Newspaper: 1.30%

## Conclusion
Random Forest Regressor performed better than Linear Regression, achieving an R² score of 98.13%. TV advertising was the most influential feature in predicting sales.

## Project Files
- Sales_Prediction.ipynb
- Advertising.csv
- README.md