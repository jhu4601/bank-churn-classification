# Bank Churn Binary Classification
**Kaggle Playground Series S4E1** | Silver Medal — Top 0.3% (out of ~5,000+ teams)

## Overview
Predicted whether a bank customer would churn (leave) based on demographic 
and account features. In Kaggle's Playground Series Season 4, 
Episode 1, finished in the top 0.3% of all participants.

## Approach
- **Class imbalance handling** via RandomOverSampler (imblearn)
- **Preprocessing pipeline** with median imputation for numeric features 
  and one-hot encoding for categoricals
- **Models trained and compared:**
  - Logistic Regression
  - K-Nearest Neighbors
  - Naive Bayes
  - Decision Tree
  - Random Forest
  - Stacking Classifier ensemble
- **Evaluation metric:** ROC-AUC (achieved 0.992 on validation set)

## Results
| Model | ROC-AUC |
|-------|---------|
| Random Forest | 0.992 |
| Stacking Ensemble | Best Kaggle submission |

## Tools Used
Python (scikit-learn, imbalanced-learn, pandas, numpy, matplotlib, seaborn)

## Competition
[Kaggle Playground Series S4E1](https://www.kaggle.com/competitions/playground-series-s4e1)
