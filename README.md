# Apartment Price Prediction (Linear and Polynomial Regression)

A simple Python project comparing linear and quadratic regression models to predict apartment prices based on floor area.

## What this script does
- **Data prep:** Calculates price per square meter and adds a squared area feature (area^2) to test for non-linearity.
- **Modeling:** Trains a **Simple Linear Regression** model and a **Polynomial Regression** model side by side.
- **Evaluation:** Splits the data into train/test sets to calculate **MAE** (Mean Absolute Error) and **RMSE** (Root Mean Squared Error) on unseen data.
- **Visualization:** Generates a comparison plot of both models against the actual data and saves it as `regression.png`.

## Requirements
Make sure you have these installed:
```bash
pip install numpy pandas scikit-learn matplotlib
