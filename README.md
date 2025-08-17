# Machine Learning for Financial Crisis Prediction

This repository contains code for the paper "**[Predicting Financial Crises: An Evaluation of Machine Learning Algorithms and Model Explainability for Early Warning Systems](https://link.springer.com/article/10.1007/s43253-024-00114-4)**". It focuses on detecting financial crises early using machine learning models, comparing Logistic Regression with k-Nearest Neighbors, Random Forest, Extremely Randomised Trees, SVM, and Neural Networks. Data from 1870–2020 and up to 15 early warning indicators were used. Random Forest and Extremely Randomised Trees outperformed Logistic Regression, and Accumulated Local Effect (ALE) plots were used for model explainability, revealing nonlinear relationships and U-shaped effects of economic indicators.

## Code Structure

* **altCrisisData.py**: Accesses alternative crisis data sources (ESRB, Laeven & Valencia).
* **doExperiment.py**: Runs experiments with various models and designs (Cross-Validation, Strict Forecasting, In-Sample).
* **prepareData.py**: Loads and processes crisis events and early warning indicators.
* **utils.py**: Custom train/test splitting methods.

Python packages used include Scikit-Learn, Pandas, Numpy, Matplotlib, and Alibi Explain for ALE plots.



