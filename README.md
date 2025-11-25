

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-ML-orange)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue)

# Titanic Survival Prediction — Multi-Model Comparison (Scikit-Learn)

A complete machine learning pipeline built using Scikit-Learn, focusing on model comparison, feature engineering, and cross-validation.  

---

## 📌 Project Overview
This project uses the classic **Titanic dataset** to evaluate multiple machine learning algorithms under the same preprocessing pipeline.  
The goal is to understand how different models behave and compare their performance reliably.

---

## 🧹 Data Preprocessing
- Handling missing values  
- Numerical feature scaling (StandardScaler)  
- Encoding categorical variables (OneHotEncoder)  
- Automated preprocessing with **ColumnTransformer**

---

## 🧠 Feature Engineering
- Extracting passenger **Title** from Name  
- Creating **FamilySize**  
- Creating **IsAlone** feature  
- Cleaning and simplifying categorical features  

---

## 🤖 Models Compared
The following ML models were trained and evaluated using 5-fold cross-validation:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- KNN  
- SVC  

---

## 📊 Cross-Validation Results

| Model               | Mean Accuracy |
|--------------------|---------------|
| **SVC**            | ~0.835        |
| Gradient Boosting  | ~0.832        |
| Logistic Regression| ~0.821        |
| KNN                | ~0.821        |
| Random Forest      | ~0.802        |

SVC achieved the highest accuracy, while Gradient Boosting provided more **stable (lower variance)** results.

---

## 📁 Repository Structure

titanic-scikit/
│
├── titanic_scikit.ipynb
├── README.md
├── requirements.txt
├── data/
└── images/

---

## 🔧 Next Steps
- Hyperparameter tuning with GridSearchCV  
- Model explainability (feature importance, SHAP)  
- Creating an ensemble / stacking model  
- Saving and exporting the final model  

---

## 👤 Author
**Mohammadtaghi Rezaei Hosseinabadi**  
Data Scientist • Industrial IoT Engineer  
LinkedIn: https://www.linkedin.com/in/mohamadtaghi65  
Kaggle: https://www.kaggle.com/mohammedtaghipro 
