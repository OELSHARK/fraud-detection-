**Credit Card Fraud Detection Project**

---

### **Project Overview**

This project is dedicated to detecting fraudulent credit card transactions using various machine learning models. The goal is to improve accuracy in identifying fraudulent transactions in a highly imbalanced dataset.

---

### **Dataset Features**

The dataset includes the following features:

- **Time:** The time elapsed between each transaction.
- **V1-V28:** Anonymized features obtained via PCA (Principal Component Analysis).
- **Amount:** Transaction amount.
- **Class:** Binary target feature (0 = Not Fraud, 1 = Fraud).

---

### **Data Preprocessing and Resampling**

1. **Data Preprocessing:**
   - Missing value handling.
   - Feature scaling using `MinMaxScaler`.
   - Removal of highly correlated features.

2. **Resampling Methods:**
   - **Random Under-Sampling (RUS):** Balances the dataset by reducing the majority class.
   - **SMOTE (Synthetic Minority Oversampling Technique):** Generates synthetic samples for the minority class.

---

### **Machine Learning Models**

The following classification algorithms were applied:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Decision Tree Classifier (DTC)
5. Random Forest Classifier (RFC)
6. Gradient Boosting Classifier (GBC)
7. XGBoost
8. Bagging Classifier
9. Stacking Classifier

---

### **Model Performance**

| **Model**                | **Accuracy** |
|--------------------------|--------------|
| Logistic Regression      | 94.52%       |
| Random Forest            | 98.76%       |
| Support Vector Machine   | 95.23%       |
| K-Nearest Neighbors      | 93.67%       |
| Decision Tree            | 91.89%       |
| Gradient Boosting        | 97.14%       |
| XGBoost                  | 98.12%       |
| Bagging Classifier       | 97.89%       |
| Stacking Classifier      | 99.21%       |

The **Stacking Classifier** performed the best, achieving an accuracy of **99.21%**.

---
