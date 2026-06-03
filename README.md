# From Scratch ML for Agricultural Emissions

A machine learning project exploring agricultural greenhouse gas emissions through regression and classification models implemented entirely from scratch using NumPy.

---

## Overview

This project investigates the relationship between agricultural practices, environmental conditions, and greenhouse gas emissions.

Instead of relying on machine learning libraries such as scikit-learn, the core learning algorithms were implemented manually to better understand optimization, regularization, and classification fundamentals.

The project includes:

- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Linear Regression
- Polynomial Regression
- Ridge Regression (L2)
- Lasso Regression (L1)
- Logistic Regression
- Gaussian Naive Bayes
- Perceptron
- Model evaluation and comparison

---

## Dataset

The repository includes a dataset containing agricultural and environmental variables such as:

- Nitrogen usage
- Irrigation levels
- Temperature
- Rainfall
- Humidity
- Greenhouse gas emissions

Target Variable:

```
Total_GHG_kgCO2e
```

Dataset file:

```
Dataset.csv
```

---

## Repository Structure

```
.
├── Dataset.csv
├── ml_for_agricultural_emissions.ipynb
└── README.md
```

---

## Machine Learning Models

### Regression

Implemented from scratch:

- Linear Regression
  - Batch Gradient Descent
  - Stochastic Gradient Descent
- Polynomial Regression (Degree 2)
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Classification

The emissions prediction problem was reformulated into a multi-class classification task using percentile-based emission categories.

Implemented from scratch:

- Logistic Regression (One-vs-Rest)
- Gaussian Naive Bayes
- Perceptron

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Key Features

- Custom train-test split implementation
- Custom feature standardization
- Manual gradient descent optimization
- Polynomial feature generation
- L1 and L2 regularization
- Custom classification metrics
- Correlation analysis and visualization
- Model comparison dashboards

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Running the Project

```
jupyter notebook ml_for_agricultural_emissions.ipynb
```

Run all notebook cells sequentially to reproduce preprocessing, training, evaluation, and visualizations.

---

## Learning Outcomes

- Implementing machine learning algorithms from first principles
- Understanding optimization through gradient descent
- Exploring bias-variance tradeoffs
- Applying regularization techniques
- Comparing regression and classification approaches
- Building complete end-to-end ML workflows
