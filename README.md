# bulldozer-price-prediction-project
# 🚜 Predicting the Sale Price of Bulldozers using Machine Learning

This project demonstrates an end-to-end machine learning workflow to predict the future sale price of bulldozers based on their characteristics and historical sales data.

## Problem Definition

**Objective:** Predict the future sale price of a bulldozer given its features and historical sales information.

## Dataset

The data is sourced from Kaggle and includes three key datasets:

1. **Train.csv:** The training dataset with historical sale prices and bulldozer attributes.
2. **Valid.csv:** The validation dataset for model evaluation.
3. **Test.csv:** The testing dataset for final model predictions.

## Workflow

This notebook follows the steps below:

1. **Data Exploration:** Analyze the dataset, check missing values, and understand feature distributions.
2. **Data Preprocessing:** Clean and preprocess the data, including handling missing values and feature engineering.
3. **Model Training:** Train machine learning models using algorithms such as Random Forest.
4. **Evaluation:** Assess model performance using metrics like Root Mean Squared Log Error (RMSLE).
5. **Prediction:** Generate predictions on the test dataset.

## Requirements

The project is built using Python. Install the following packages:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

Install the required libraries with:

```bash
pip install -r requirements.txt
