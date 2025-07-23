# Credit Card Default Prediction

This project uses a dataset of credit card clients to predict the likelihood of payment default in the next month using various machine learning models.

## 🔍 Overview

- Balanced the dataset using undersampling
- Engineered new features: average delay (`AVG_PAY`) and late payment indicator (`ANY_LATE`)
- Trained models:
  - Logistic Regression
  - Decision Tree
  - Naive Bayes
- Evaluated performance using classification report and confusion matrix

## 📊 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

## 📁 Dataset

`Credit_Card_Default.csv`

- Target: `default.payment.next.month`
- Feature set includes payment history, credit limit, and custom features

## 🧠 Results

Model performance evaluated using:
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🚀 Run it locally

```bash
pip install -r requirements.txt
```
