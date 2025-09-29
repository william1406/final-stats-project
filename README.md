# Final Project - Statistics & Data Science

This repository contains my final project for a university course in statistics & data science.  
The goal of the project was to analyze hospital readmission data and apply different machine learning models to predict whether a patient would be readmitted within 30 days.

---

## 📂 Contents
- `project.ipynb` – Jupyter Notebook with all preprocessing, modeling, and evaluation code.
- `final_report.pdf` – Final report (in PDF) with explanations of methods, results, and conclusions.

---

## 🔍 Project Overview
- **Dataset**: Hospital diabetes readmission dataset (1999–2008).  
- **Objective**: Predict short-term readmission (<30 days).  
- **Methods**:
  - Preprocessing (handling missing values, encoding, scaling).
  - L1-regularized logistic regression (feature selection).
  - PCA for dimensionality reduction.
  - Machine learning models: Logistic Regression, KNN, Kernel SVM.
  - Ensemble method (majority voting).

---

## 📊 Key Results
- Logistic Regression (L2 regularization): **Best test F1 score = 0.251**.
- Kernel SVM (RBF approximation): **Test F1 = 0.240**.
- KNN: Poor performance due to high dimensionality (F1 = 0.039).
- Majority vote of models gave a small improvement (**F1 = 0.255**).
- PCA showed that **hospital usage patterns and medication history** explain much of the variance.

---

## 🛠️ Tools & Libraries
- Python, Jupyter Notebook
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`
- Dimensionality reduction: TruncatedSVD
- Multiple testing correction: Benjamini–Hochberg

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/william1406/final-stats-project.git
