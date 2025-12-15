# Wine Quality Classification using Machine Learning

## Overview

Machine learning project focused on binary classification of wine quality (high vs. low) using physicochemical features from the Wine Quality (Red Wine) dataset.

## Objective

To predict wine quality categories based on chemical properties and evaluate the performance of different classification algorithms, with the goal of supporting automated quality control in the wine industry.

## Dataset

* Wine Quality Dataset (Red Wine)
* Fully numerical features
* Target variable transformed into two classes: **High Quality** and **Low Quality**

Key features include acidity, alcohol content, sulphates, pH, density, and sulfur dioxide levels.

## Methodology

The project follows a structured machine learning workflow:

* Exploratory Data Analysis (EDA)
* Feature engineering and target transformation
* Outlier analysis
* Feature scaling (StandardScaler)
* Model training and comparison

## Models Evaluated

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest
* Bagging
* Gradient Boosting (XGBoost)

## Evaluation Metrics

* ROC AUC (primary metric)
* Accuracy
* F1-score

## Results

* **Best model:** XGBoost
* **ROC AUC:** 0.88
* **Accuracy:** 0.82
* **F1-score:** 0.83

Ensemble tree-based models outperformed linear and distance-based models, showing strong capability to capture non-linear relationships between physicochemical variables.

## Key Insights

* Alcohol and sulphates were among the most influential features.
* Tree-based ensemble methods are well-suited for wine quality prediction.
* The model demonstrates potential for automating and standardizing wine quality assessment.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Google Colab
* Matplotlib / Seaborn

## Author

Nicolas Salinas

---

This project is part of a Data Science training program and is intended for educational and portfolio purposes.

