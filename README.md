# 💳 Credit Card Fraud Detection

A machine learning-based system designed to detect fraudulent credit card transactions with high precision, leveraging advanced feature engineering, model tuning, and real-world imbalanced datasets.  

This project was developed as part of the **MindBridge Data Science Challenge**, where the goal was to build a robust fraud detection model capable of performing well under highly imbalanced conditions and delivering meaningful, real-world results.  

---

## 📌 Overview

Credit card fraud is a major challenge in the financial sector, with billions lost annually. This project builds and evaluates models to classify transactions as fraudulent or legitimate, with a strong focus on **precision**, **recall**, and **PR AUC** to minimize false positives and maximize detection accuracy.  

The system uses:  
- **Python** for data processing and modeling  
- **XGBoost**, **Random Forest**, and **Logistic Regression** for classification  
- **Imbalanced-learn** techniques like SMOTE and class weighting  
- Advanced **feature engineering** to boost predictive performance  

---

## 🚀 Features

- **Data Cleaning & Preprocessing**  
  - Handling missing values and scaling features  
  - Encoding categorical features (if applicable)  
  - Outlier detection and removal  

- **Feature Engineering**  
  - Time-based features (hour of day, day of week)  
  - Transaction frequency metrics  
  - Digit-based entropy and repeat ratio features   

- **Fraud Detection Pipeline**  
  - Train-test split with stratification  
  - Pipeline for preprocessing + model inference  
  - Real-time prediction ready  

---

## 🛠 Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Imbalanced-learn  
- **Tools:** Jupyter Notebook, Git, VS Code  

---

## 📊 Results

| Model               | PR AUC  | Precision
|---------------------|---------|-----------
| XGBoost             | 0.8594  | 0.9474
| Random Forest       | 0.7589  | 0.6790
| Logistic Regression | 0.4746  | 0.8657
| Neural Net          | 0.7962
> **Note:** XGBoost with hyperparameter tuning to avoid overfitting achieved the highest PR AUC of **0.8165**.
