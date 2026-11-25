# BIA – Lesson 6: Machine Learning Basics (Assignment)

**Student:** Meryulis Zambrano

**Program:** Diploma in Business Intelligence Analyst – Willis College

**Course:** Introduction to AI

This repository contains the Assignment for Lesson 6: **House Price Prediction using the California Housing dataset**. I follow a simple machine learning project cycle: data loading → EDA and preprocessing → model training → model evaluation → prediction.

## Files

| File | Description |
|------|-------------|
| `Lesson_6_ml_basic_assignment_Meryulis.ipynb` | Colab notebook with code, comments and outputs |
| `Lesson_6_ml_basic_assignment_Meryulis.pdf` | Notebook exported as PDF with outputs |

## Summary

- Loaded the dataset with `fetch_california_housing()` and converted it to a DataFrame.
- Inspected the data with `.head()`, `.info()` and `.describe()`; checked for null values.
- Created the function `visualizeHousingData()` to plot several features against `MedHouseVal`.
- Trained a Linear Regression model (80/20 split) and evaluated it with RMSE and R² (R² ≈ 0.58).
- Predicted the house value for a new set of inputs.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Google Colab, GitHub.
