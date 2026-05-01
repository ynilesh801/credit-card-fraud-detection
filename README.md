# 💳 Credit Card Fraud Detection

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using machine learning and deep learning models.

## 📊 Dataset
- ~568K transactions
- Features: PCA-transformed (V1–V28), Amount
- Target: Fraud (0 = Legit, 1 = Fraud)
- Dataset link: https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023

## ⚠️ Key Challenge
Fraud detection is a highly sensitive classification problem where identifying fraudulent cases (Recall) is more important than overall accuracy.

## 🔧 Approach
- Data Cleaning & EDA
- Train-Test Split (to avoid data leakage)
- Feature Scaling using StandardScaler
- Models:
  - Logistic Regression
  - Neural Network (TensorFlow/Keras)

## 📈 Evaluation Metrics
- Confusion Matrix
- Precision, Recall, F1-score

## 🧠 Key Learnings
- Avoided data leakage by applying scaling after splitting
- Understood importance of recall in fraud detection
- Compared ML vs Deep Learning performance

## 🚀 Future Improvements
- Handle class imbalance realistically
- Add ROC-AUC & PR-AUC curves
- Threshold tuning for better fraud detection

## 🛠️ Tech Stack
Python | Pandas | Scikit-learn | TensorFlow | Matplotlib | Seaborn
