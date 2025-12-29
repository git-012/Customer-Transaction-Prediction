# 🧾 Customer Transaction Classification using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a customer will make a transaction based on historical behavioral and profile-related data.  
The problem is formulated as a **binary classification task**, where the goal is to identify transaction likelihood using machine learning models.

---

## 📊 Dataset
- Contains customer activity and profile-based features
- Target variable:
  - `is_transaction`
    - `1` → Customer made a transaction
    - `0` → No transaction

---

## ⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Machine Learning Models Implemented
- Logistic Regression ✅ *(Final Model)*
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost

---

## ✅ Final Model Selection
**Chosen Model:** Logistic Regression  

**Reasons for Selection:**
- Simple and interpretable
- Good generalization performance
- Lower risk of overfitting compared to complex models

**Performance Metrics:**
- **Accuracy:** 78%
- **AUC Score:** 85%

---

## 📈 Model Evaluation
The following evaluation techniques were used:
- Confusion Matrix
- ROC Curve
- AUC Score

These metrics helped assess classification performance and trade-offs between sensitivity and specificity.

---

## 📁 Project Files
- `Customer_Transaction_Prediction_Final.ipynb`  
  → Complete data analysis, feature engineering, model training, and evaluation

---

## 📌 Summary & Future Work
The final model demonstrates strong predictive capability, particularly in terms of AUC performance.  
Further improvements may be achieved through:
- Advanced feature engineering
- Hyperparameter tuning
- Trying ensemble techniques



