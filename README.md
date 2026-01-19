Name-Swastik
Roll no-102316020
# Credit Card Fraud Detection using Sampling Techniques

## 📌 Project Overview
This project focuses on handling **class imbalance** in Credit Card Fraud Detection using various **sampling techniques** and **machine learning models**.  
The goal is to analyze how different resampling strategies affect model performance.

This repository contains both:
- A **Jupyter Notebook** for experimentation and analysis
- A **combined Python script** for clean execution and reproducibility

---


---

## 📊 Dataset Description
- **Dataset**: Credit Card Transactions
- **Target Column**: `Class`
  - `0` → Legitimate Transaction
  - `1` → Fraudulent Transaction
- The dataset is **highly imbalanced**, with fraud cases forming a very small percentage.

---

## ⚙️ Techniques Implemented

### 🔹 Sampling Methods
The following sampling strategies are applied and compared:

- Original Imbalanced Data
- Random Under Sampling
- Random Over Sampling
- SMOTE (Synthetic Minority Over-sampling Technique)
- NearMiss
- SMOTE + Tomek Links

---

### 🔹 Machine Learning Models
Each sampled dataset is trained and evaluated using:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Evaluation Metrics
Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🧪 Project Workflow
1. Load and explore the dataset  
2. Analyze class imbalance  
3. Apply different sampling techniques  
4. Scale features  
5. Train machine learning models  
6. Evaluate and compare performance  
7. Identify the best sampling–model combination  

---

## 🛠️ Technologies & Libraries Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Seaborn

---



