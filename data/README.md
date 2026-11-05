
# Machine Learning-Based Tender Final Price Prediction

## Project Overview

This project focuses on predicting public procurement tender final prices using machine learning and deep learning techniques.

The study uses the **Global Public Procurement Dataset (GPPD)**, a large-scale dataset containing public procurement records from multiple countries. Germany was selected as the target country for this project, and the analysis and modeling processes were performed using German procurement data.

The main objective is to develop predictive models, compare their performance, and investigate how different machine learning approaches perform in estimating tender final prices.

## Project Objectives

- Analyze large-scale public procurement data.
- Perform data cleaning and preprocessing.
- Handle missing values and improve data quality.
- Apply feature engineering techniques.
- Develop and compare machine learning and deep learning models.
- Optimize model hyperparameters.
- Evaluate model performance using statistical metrics.
- Analyze prediction errors and model behavior.

## Dataset

**Dataset:** Global Public Procurement Dataset (GPPD)

- Dataset scope: Multiple countries
- Selected country: Germany
- Target variable: `tender_finalpriceUsd`
- Selected data file: `DE_DIB_2023.csv.gz`

The original dataset contains procurement records from different countries. For this study, German procurement records were selected for analysis and model development.

## Methodology

The project follows a structured machine learning workflow:

1. Data Loading and Exploration
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Missing Value Analysis
4. Missing Value Imputation
5. Feature Engineering
6. Data Transformation and Encoding
7. Model Development
8. Hyperparameter Optimization
9. Cross-Validation
10. Model Evaluation and Residual Analysis

## Machine Learning and Deep Learning Models

The following approaches were implemented and evaluated:

- **XGBoost:** Gradient boosting-based regression model.
- **Neural Networks (Keras):** Deep learning-based regression model.
- **AutoGluon:** Automated machine learning framework for model training and comparison.

### Hyperparameter Optimization

- **Optuna:** Used for hyperparameter optimization of the XGBoost model.

### Data Processing Techniques

- Polars
- KNN Imputation
- Feature Engineering
- Logarithmic Transformation
- Power Transformation
- Categorical Feature Encoding
- Sample Weighting

### Model Evaluation

Model performance was assessed using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R²)
- Residual Analysis

A 9-fold cross-validation strategy was also implemented to evaluate model performance across different data splits.

## Technologies and Tools

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Processing | Polars, NumPy |
| Machine Learning | XGBoost, Scikit-learn |
| Deep Learning | Keras |
| Automated Machine Learning | AutoGluon |
| Hyperparameter Optimization | Optuna |
| Experiment Tracking | Weights & Biases |
| Development Environment | Google Colab |

## Project Structure

```text
tender-final-price-prediction/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── tender_final_price_prediction.ipynb
│
├── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Development Environment

The project was developed using Python in Google Colab.

The notebook contains the data processing, feature engineering, model development, optimization, and evaluation stages.

Dataset access and installation instructions will be provided separately.

## Acknowledgements

This project was developed during an internship at TÜBİTAK SAGE as part of a study on large-scale data analysis and machine learning-based tender price prediction.
