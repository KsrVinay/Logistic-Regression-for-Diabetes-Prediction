# Logistic Regression for Diabetes Prediction

## Overview
This project applies **Logistic Regression** to predict the likelihood of diabetes based on a given dataset (`diabetes2.csv`). The notebook preprocesses the data, trains a model, and evaluates its performance.

## Dataset
The dataset contains multiple health-related features:
- **Pregnancies**
- **Glucose**
- **BloodPressure**
- **SkinThickness**
- **Insulin**
- **BMI**
- **DiabetesPedigreeFunction**
- **Age**
- **Outcome** (Target variable: 0 = No Diabetes, 1 = Diabetes)

## Steps in the Notebook
1. **Load Data**: Reads the `diabetes2.csv` file using Pandas.
2. **Preprocessing**:
   - Converts columns to numeric values.
   - Splits data into features (`X`) and target (`y`).
   - Performs train-test split (80-20) with stratification.
   - Standardizes numerical features using `StandardScaler`.
3. **Model Training**:
   - Implements **Logistic Regression** using Scikit-learn.
4. **Evaluation**:
   - Displays dataset summary and value counts.
   - Computes accuracy and classification metrics.

## Requirements
To run this notebook, install the following dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
