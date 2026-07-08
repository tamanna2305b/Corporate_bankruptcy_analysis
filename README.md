# Corporate Bankruptcy Prediction using Machine Learning

## Overview

This project explores the use of machine learning to predict corporate bankruptcy using financial statement data from Taiwanese companies. I covered data cleaning, exploratory data analysis, preprocessing, model training and evaluation to identify the most effective model for bankruptcy prediction.

The project compares four different classification algorithms and evaluates their performance using multiple metrics suitable for imbalanced datasets.

---

## Dataset

- **Source:** UCI Machine Learning Repository / Kaggle
- **Records:** 6,819 companies
- **Features:** 95 financial indicators
- **Target Variable:** Bankrupt? (0 = Non-bankrupt, 1 = Bankrupt)

---

## Models Compared

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Model Performance

| Model | Accuracy | ROC-AUC |
|--------|---------:|---------:|
| Logistic Regression | 96.2% | 0.852 |
| Decision Tree | 96.0% | 0.683 |
| Random Forest | 97.2% | 0.952 |
| XGBoost | 96.8% | **0.961** |

XGBoost achieved the highest ROC-AUC score, making it the strongest overall model for this dataset.

---

## Key Findings

- The dataset was highly imbalanced, making metrics such as Precision, Recall and ROC-AUC more informative than accuracy alone.
- Profitability and debt-related financial indicators showed the strongest relationship with bankruptcy.
- Ensemble learning methods outperformed the simpler baseline models.
- XGBoost achieved the best overall predictive performance.

---

## Future Improvements

- Address class imbalance using SMOTE
- Deploy the best-performing model as a web application
- Test additional ensemble learning algorithms

