# MetroFlow: Public Transport Delay Risk Analysis

## Project Overview
This repository contains a predictive modeling project focused on analyzing and forecasting the risk of severe delays in public transit networks. 

## Methodology & Models
The analysis compares several machine learning approaches to identify the most robust predictive model. The workflow includes:
* **Linear Models:** Logistic Regression utilizing L1 and L2 regularization to handle feature importance and prevent overfitting.
* **Ensemble Methods:** Random Forests and Gradient Boosting algorithms designed to capture complex, non-linear relationships in the transit data.

## Evaluation Metrics
To accurately assess performance on potentially imbalanced data (where severe delays are minority events), the models are evaluated and compared using:
* **PR-AUC** (Precision-Recall Area Under the Curve)
* **ROC-AUC** (Receiver Operating Characteristic Area Under the Curve)

## Repository Structure
* `MLfinalmasterpieceversion.ipynb`: The main Python notebook containing data exploration, preprocessing, model training, and evaluation.
