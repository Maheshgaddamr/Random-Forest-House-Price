🌳 House Price Prediction - Random Forest
## Overview
Improved House Price Prediction using Random Forest
on California Housing Dataset.
Compared results with Linear Regression model.

## Results
| Metric    | Value         |
|-----------|---------------|
| Algorithm | Random Forest |
| R² Score  | 0.8164        |
| RMSE      | $49,047       |
| Dataset   | California Housing |

## Model Comparison
| Model             | R² Score | RMSE     |
|-------------------|----------|----------|
| Linear Regression | 0.6254   | $70,060  |
| Random Forest     | 0.8164   | $49,047  |
| Improvement       | +0.1910  | -$21,013 |

## What Improved
- R² Score jumped from 0.625 to 0.816
- RMSE reduced by $21,013
- Random Forest 19% more accurate
  than Linear Regression

## Steps Followed
- Loaded California Housing Dataset
- Handled missing values (total_bedrooms)
- Encoded categorical feature (ocean_proximity)
- Split data Train 80% and Test 20%
- Trained Random Forest (99 trees)
- Evaluated using R², MSE, RMSE
- Compared with Linear Regression

## Visualizations
- ✅ Feature Importance Chart
- ✅ Actual vs Predicted Plot
- ✅ Model Comparison

## Key Findings
- median_income is strongest predictor
- Random Forest handles non-linear 
  data much better than Linear Regression
- 100 decision trees combined give
  more accurate predictions

## Why Random Forest is Better
- Builds 99 decision trees
- Combines all trees for final prediction
- Handles complex patterns in data
- Reduces overfitting automatically

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
## 🔗 Related Projects
| Project | Algorithm | R² Score | Link |
|---------|-----------|----------|------|
| House Price Prediction v1 | Linear Regression | 0.6254 | [Click Here](https://github.com/Maheshgaddamr/House-Price-Prediction) |
| House Price Prediction v2 | Random Forest | 0.8164 | This Project |
