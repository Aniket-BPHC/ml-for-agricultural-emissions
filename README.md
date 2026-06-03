# ML for Agricultural Emissions

Machine learning project exploring greenhouse gas emissions in agriculture through exploratory data analysis, regression modeling, regularization techniques, and classification algorithms implemented from scratch.

---

## Overview

Agricultural activities are a significant contributor to greenhouse gas emissions. This project investigates how environmental conditions and farming practices influence emissions using a combination of statistical analysis and machine learning techniques.

The project includes:

* Exploratory Data Analysis (EDA)
* Linear Regression
* Polynomial Regression
* L1 and L2 Regularization
* Classification Reformulation
* Model Evaluation and Comparison

The emphasis is on understanding machine learning fundamentals through custom implementations and empirical analysis.

---

## Dataset

The repository includes a structured agricultural emissions dataset containing information such as:

* Crop type
* Fertilizer usage
* Irrigation patterns
* Temperature
* Rainfall
* Humidity
* Greenhouse gas emission indicators

Target Variable:

* Total greenhouse gas emissions (CO₂-equivalent)

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

## Features Implemented

### Data Preprocessing

* Dataset inspection and cleaning
* Missing value analysis
* Numerical and categorical feature identification
* Feature selection and scaling

### Exploratory Data Analysis

* Descriptive statistics
* Histograms and boxplots
* Correlation analysis
* Scatter plot visualization
* Distribution analysis

### Regression Models

Implemented and evaluated:

* Linear Regression
* Batch Gradient Descent
* Stochastic Gradient Descent
* Polynomial Regression (Degree 2)
* Ridge Regression (L2)
* Lasso Regression (L1)

Evaluation Metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

### Classification Models

The emissions prediction problem was reformulated as a classification task.

Implemented:

* Logistic Regression
* Naive Bayes
* Perceptron

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Learnings

* Building machine learning models from first principles
* Understanding optimization through gradient descent
* Applying regularization to control overfitting
* Comparing regression and classification approaches
* Performing end-to-end exploratory data analysis

---

## Running the Project

Open the notebook and run all cells:

```
jupyter notebook ml_for_agricultural_emissions.ipynb
```

The notebook contains the complete workflow, from data preprocessing to model evaluation and visualization.

---

## Notes

This project focuses on developing a deeper understanding of machine learning algorithms and model behavior through implementation, experimentation, and analysis.
