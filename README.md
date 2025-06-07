# Understanding Magazine Subscription Behavior

This project aims to help a magazine company understand the factors behind a recent decline in subscriptions. Using customer and campaign data, multiple classification models were built to predict subscription behavior and identify key variables influencing customer decisions.

---

## Problem Statement

Despite people spending more time at home, magazine subscriptions declined last year. The company suspects changes in customer behavior or ineffective campaigns. This project explores the dataset to uncover insights and build models that can accurately predict which customers are likely to subscribe.

---

## Objectives

- Clean and preprocess customer marketing data
- Build multiple classification models to predict subscription behavior
- Compare model performance using accuracy, precision, and recall
- Identify key drivers behind customer subscription decisions

---

## Task Summary

### Task 1: Data Cleaning
- Handled missing values
- Encoded categorical variables
- Normalized continuous features
- Ensured high-quality, ready-to-model data

### Task 2: Logistic Regression
- Built a baseline logistic model
- Identified significant variables: `Income`, `Recency`, `MntWines`, `WebPurchases`
- Interpreted model coefficients for business insight

### Task 3: Support Vector Machine (SVM)
- Tuned kernel and hyperparameters
- Achieved moderate accuracy
- Compared decision boundary with logistic regression

### Task 4: Decision Tree (Depth = 4)
- Constructed a shallow interpretable tree
- Visualized splitting criteria
- Compared tree structure to insights from other models

---

## Model Comparison

| Model           | Accuracy | Precision | Recall | F1 Score |
|----------------|----------|-----------|--------|----------|
| Logistic Model | 0.88     | 0.86      | 0.90   | 0.88     |
| SVM            | 0.85     | 0.84      | 0.85   | 0.84     |
| Decision Tree  | 0.87     | 0.85      | 0.89   | 0.87     |

> **Recommendation:** The **Logistic Regression** model is both accurate and interpretable, making it ideal for business decision-making. Key variables influencing subscription behavior include `Income`, `Recency`, `WebPurchases`, and `MntWines`.

---

## Repository Structure

```bash
magazine-subscription-modeling/
├── Magazine Subscription Behaviour.ipynb     # Main analysis notebook
├── Magazine Subscription Behaviour.html      # Exported HTML version
├── marketing_campaign.xlsx                   # Dataset used
├── Magazine_Data_Dictionary.docx                      # (optional) Variable descriptions
└── README.md                                 # Project overview
