![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-ML-orange)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue)

# Titanic Survival Prediction — Multi-Model Comparison (Scikit-Learn)
A complete machine learning pipeline built using Scikit-Learn, focusing on model comparison, feature engineering, and cross-validation.
📌 Project Overview
This project uses the classic Titanic dataset to evaluate multiple ML algorithms under the same preprocessing pipeline.
The goal is to understand how different models behave and compare their performance reliably.
🚀 Features
Clean data preprocessing using ColumnTransformer


Feature engineering (Title, FamilySize, IsAlone, etc.)


Multiple ML models compared:


Logistic Regression


Random Forest


Gradient Boosting


KNN


SVC


5-Fold Cross-Validation for stable evaluation


Model comparison visualization


Hyperparameter tuning (coming soon)


📊 Model Performance (Cross-Validation Accuracy)


Model
Accuracy
SVC
~0.835
Gradient Boosting
~0.832
Logistic Regression
~0.821
KNN
~0.821
Random Forest
~0.802



🧠 What I Learned
Importance of preprocessing consistency


How different algorithms generalize on small datasets


Role of variance and stability in model selection


Impact of feature engineering on classical ML


📂 Repository Structure

titanic-scikit/
│
├── titanic_scikit.ipynb
├── README.md
├── requirements.txt
├── data/
└── images/

