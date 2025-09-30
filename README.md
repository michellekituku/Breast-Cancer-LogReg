# 🩺 Breast Cancer Classification with Logistic Regression

This project uses **Logistic Regression** to classify tumors as malignant or benign using the Breast Cancer dataset from scikit-learn.  
The focus is on **model performance, the effect of regularization (C), and feature interpretability**.  

---

## 📊 Project Overview
- Preprocessed the Breast Cancer dataset into features + labels.  
- Trained Logistic Regression with different regularization strengths (`C = 0.001, 1, 100`).  
- Compared training and testing accuracy across models.  
- Visualized coefficient magnitudes to interpret which features were most important.  

---

## 🛠️ Libraries Used
- `scikit-learn`
- `pandas`
- `matplotlib`
- `seaborn`

---

## 📈 Results
- Best test accuracy achieved: **96.5%** with `C=1`.  
- Coefficient visualization revealed **worst radius, mean concavity, and worst area** as key predictive features.  

---

## 📷 Visualizations
- Logistic regression coefficient plots across different `C` values.  
- Accuracy comparison between training and test sets.  

