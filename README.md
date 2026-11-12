# House Price Prediction Using Machine Learning

# Project Overview

This project uses machine learning to predict house selling prices from housing-related features. It demonstrates data preprocessing, model comparison, cross-validation, feature importance, and model evaluation.

## Problem Statement

House prices depend on several factors, including property size, quality, and other characteristics. The goal is to train a regression model that estimates a house's selling price from available data.

## Dataset

The project uses housing data to train and evaluate regression models.

**Dataset source:** [Verify and add the exact dataset source used in the notebook.]

The target variable is `SalePrice`, representing the actual selling price.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn(for ML)
* Google Colab
* GitHub for version control and project hosting

Add Matplotlib and Seaborn here only if you used them in your notebook.

## Machine Learning Workflow

1. Load and inspect the housing dataset.
2. Explore the data and identify data-quality issues.
3. Handle missing values and prepare numerical and categorical features.
4. Split the data into training and testing sets.
5. Train and compare regression models.
6. Use five-fold cross-validation for model comparison.
7. Evaluate the selected model using MAE, RMSE, and R².
8. Save the trained model and export the results.

## Models Compared

* Linear Regression
* Ridge Regression
* Random Forest
* Gradient Boosting

**Selected model:** Gradient Boosting, based on the recorded model comparison and cross-validation results.

## Model Evaluation Results

The following results are recorded in the project:

| Metric                         |     Result |
| ------------------------------ | ---------: |
| Mean Absolute Error (MAE)      | $16,922.49 |
| Root Mean Squared Error (RMSE) | $30,265.12 |
| R² Score                       |     0.8806 |

MAE measures the average absolute prediction error. RMSE gives more weight to larger errors. R² measures how much variation in the target is explained by the model on the evaluated dataset.

## Example Prediction

One recorded example:

* Actual house price: $154,500.00
* Predicted house price: $142,549.85
* Absolute error: $11,950.15

This is an example prediction, not a guarantee of performance for every house.

## Project Files

* `Prateek_D_S_House_Price_pridiction(ML_PROJECT).ipynb` — notebook for analysis and model training
* `house_price_model.pkl` — saved model file
* `model_metrics.json` — model evaluation metrics
* `model_comparison.csv` — comparison of models
* `cross_validation_results.csv` — cross-validation results
* `feature_importance.csv` — feature importance results

## How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Download and provide the same dataset used by the notebook.
4. Install any required packages that are not already available.
5. Run the notebook cells in order.
6. Review the evaluation results and predictions.

Note: The notebook and saved model should be verified to ensure the instructions work from a fresh environment.

## Future Improvements

* Validate the complete preprocessing and prediction pipeline.
* Tune model hyperparameters using cross-validation.
* Analyze prediction errors and improve reproducibility.
* Build a simple prediction interface as a future enhancement.

## Author

Prateek Suryavanshi

GitHub: [House Price Prediction ML Repository](https://github.com/prateek-suryavanshi465/House-Price-Prediction-ML)

