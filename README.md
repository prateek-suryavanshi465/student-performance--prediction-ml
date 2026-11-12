# House Price Prediction Using Machine Learning

## Overview
A regression project predicting house sale prices using property
characteristics from the Ames Housing dataset.

## Objectives
- Explore and clean housing data.
- Handle missing values with preprocessing pipelines.
- Encode categorical features and scale numerical features.
- Compare four regression algorithms.
- Evaluate predictions using MAE, RMSE and R-squared.
- Analyze feature importance.

## Dataset
- Source: OpenML, house_prices, version 1
- Original dataset: 1,460 rows and 81 columns
- Target: SalePrice
- Identifier column removed before modeling.

## Models Compared
- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Model Selection
Gradient Boosting was selected based on the lowest mean
5-fold cross-validation RMSE.

## Held-out Test Results
- MAE: 16,922.49
- RMSE: 30,265.12
- R-squared: 0.8806

Errors are expressed in the dataset's price units (USD).

## Important Features
OverallQual and GrLivArea ranked highly in the model's
feature-importance analysis. Feature importance does not
imply causation.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn,
Google Colab and Joblib.

## Files
- House price prediction notebook (.ipynb)
- house_price_model.pkl
- model_metrics.json
- model_comparison.csv
- cross_validation_results.csv
- feature_importance.csv

## Limitations
Performance is based on one train/test split and cross-validation
on the training set. Results may not generalize to other markets
or current property prices. The model is an educational project,
not a professional property valuation.

## Reproducibility
The notebook contains the data loading, preprocessing,
training and evaluation workflow. The saved model includes
the preprocessing pipeline.
