# Magazine Subscription Behaviour

This repository contains an end-to-end data analytics project aimed at understanding and predicting customer behavior regarding magazine subscriptions. Using a real-world marketing dataset, we analyze what drives subscription decisions and build predictive models to assist in business strategy and customer targeting.

---

## Problem Statement

A magazine company experienced a decline in subscriptions despite expecting an increase due to more people spending time at home. This project explores customer demographics, purchase behavior, and campaign responses to identify key factors influencing subscriptions.

---

## Project Goals

- Perform thorough **data cleaning** and preprocessing.
- Build and evaluate **three classification models** to predict customer subscription behavior:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
- **Compare model performance** (accuracy, precision, recall).
- Recommend the best-performing model based on business insights.
- Identify key features influencing subscription decisions.

---

## Tasks Overview

### Task 1: Data Cleaning
- Handled missing values and outliers
- Encoded categorical variables
- Scaled numeric features as needed

### Task 2: Logistic Regression
- Evaluated significant predictors (e.g., Income, WebPurchases, Recency)
- Analyzed coefficient impact and interpretability

### Task 3: SVM Model
- Built an SVM classifier
- Compared accuracy against logistic regression

### Task 4: Decision Tree (Depth = 4)
- Developed a simple tree for explainability
- Compared structure and variable importance with other models

### Task 5: Model Comparison
| Model             | Accuracy | Precision | Recall |
|------------------|----------|-----------|--------|
| Logistic Model    | XX%      | XX%       | XX%    |
| SVM               | XX%      | XX%       | XX%    |
| Decision Tree     | XX%      | XX%       | XX%    |

> Final Recommendation: Based on model performance and interpretability, we recommend **[best model]**. Key drivers include **Income**, **Recency**, and **Online Purchases**.

---


## Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- VS Code
- GitHub

---

## Repository Structure

```bash
Subscription-Behaviour/
├── Magazine Subscription Behaviour.html     # Exported HTML report of the notebook
├── Magazine Subscription Behaviour.ipynb    # Main Jupyter Notebook with analysis and models
├── Magazine_Data_Dictionary.docx            # Data dictionary describing all features
├── marketing_campaign-1-1.xlsx              # Original marketing dataset
└── README.md                                # Project documentation (this file)

Thank you!

