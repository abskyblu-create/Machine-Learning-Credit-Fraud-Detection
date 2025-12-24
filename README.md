# Credit Card Fraud Detection

This project focuses on credit card fraud detection using machine learning techniques on a highly imbalanced real-world dataset. The objective is to explore, evaluate, and compare multiple models while addressing the challenges introduced by extreme class imbalance.

## Video link - https://youtu.be/sgIN_kiTUHQ

## Project structure
- `notebooks/`: Jupyter notebooks covering data exploration, baseline models, advanced ensemble methods, and balanced dataset evaluation.
- `data/`: Dataset directory (not included in the repository).
- `reports/`: Final project report.
- `requirements.txt`: Python dependencies.

## Models explored
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM
- Ensemble methods (Bagging, Voting)

## Evaluation metrics
Due to class imbalance, evaluation relies on:
- Recall
- F1-score
- ROC-AUC
- PR-AUC

## Setup
```bash
pip install -r requirements.txt
