# BIA – Lesson 6: Machine Learning Basics

**Student:** Meryulis Zambrano

**Program:** Diploma in Business Intelligence Analyst – Willis College

**Course:** Introduction to AI

This repository contains the Lab Activity and the Assignment for Lesson 6, where I follow a simple machine learning project cycle:
data loading → EDA and preprocessing → model training → model evaluation → prediction.

## Files

| File | Description |
|------|-------------|
| `Lesson_6_lab_ML_Basics.ipynb` | Lab: Future Sales Prediction using advertising spend (TV, radio, newspaper) and Linear Regression |
| `advertising.csv` | Dataset used in the lab (200 rows) |
| `Lesson_6_ml_basic_assignment.ipynb` | Assignment: House Price Prediction using the California Housing dataset from scikit-learn |
| PDF files | Notebooks exported with their outputs |

## Lab – Future Sales Prediction
- Checked for null values and visualised each platform against sales with Plotly.
- Created a reusable function `visualizeSalesData()` to plot any platform.
- Trained a Linear Regression model (80/20 split).
- Evaluated it with R², MAE, MSE, RMSE, an Actual vs Predicted plot and 5-fold cross-validation (R² ≈ 0.90).
- Discussed why the model is not fully reliable (small dataset, missing factors, linear assumption).

## Assignment – California House Price Prediction
- Loaded the dataset with `fetch_california_housing()` and converted it to a DataFrame.
- Inspected the data with `.head()`, `.info()` and `.describe()`; checked for null values.
- Created the function `visualizeHousingData()` to plot several features against `MedHouseVal`.
- Trained a Linear Regression model (80/20 split) and evaluated it with RMSE and R² (R² ≈ 0.58).
- Predicted the house value for a new set of inputs.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, Plotly, scikit-learn, Google Colab, GitHub.
