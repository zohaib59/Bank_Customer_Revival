# Bank_Customer_Revival
# 🔍 Bank Customer Revival Classifier

A production-ready machine learning project aimed at predicting **customer revival opportunities** in banking — tailored for real-world deployment and stakeholder impact.

## 🧠 Objective
Identify dormant customers with high potential for reactivation across products like Fixed Deposits, Mutual Funds, NPS, and more.

## 🗂️ Dataset
- 70,000 real-world simulated records
- Features include transaction history, FD maturity, mobile app usage, sentiment score, PAN verification, support activity, product cross-usage
- No nulls, duplicates, NaNs, or toy data

## 🛠️ Features
- Label encoding, feature scaling, outlier detection
- Balanced binary classification (`revival_flag`)
- Modular pipeline across 12+ classifiers (Logistic, XGB, CatBoost, Neural Net, etc.)
- SHAP explanation support
- Confusion matrices, F1, precision/recall metrics

## 📈 Output
Generates revival likelihood for customers, enabling:
- Proactive cross-selling
- RM targeting
- Dashboarding and alert systems

## 📦 Models Supported
- Logistic Regression
- Ridge Classifier
- Random Forest, Extra Trees
- GradientBoosting, AdaBoost
- XGBoost, CatBoost, LGBM
- MLP Neural Network
