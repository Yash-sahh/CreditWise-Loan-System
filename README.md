# CreditWise Loan System

CreditWise is an end-to-end supervised machine learning pipeline built to predict loan approvals. In the financial sector, accurate risk assessment is critical. This project leverages data-driven insights to optimize the credit decision-making process by identifying whether a loan application should be approved or denied.

---

## 🚀 Features & Pipeline Architecture

The project implements a complete binary classification workflow, structured as follows:

* **Exploratory Data Analysis (EDA):** Investigated data distributions, identified correlations, handled missing values, and uncovered key insights regarding borrower profiles.
* **Feature Engineering:** Transformed and scaled raw data into optimized inputs to enhance model interpretability and predictive accuracy.
* **Model Implementation:** Built and trained multiple supervised learning algorithms to compare performance:
  * K-Nearest Neighbors (KNN)
  * Logistic Regression
  * Naive Bayes
* **Model Evaluation:** Evaluated performance using strict financial-domain metrics, focusing on balancing **Precision**, **Recall**, and **F1-Score** to minimize credit risk while maximizing approval efficiency.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn

---

## 📊 Evaluation Metrics Focus

In credit risk modeling, misclassifying a bad loan (False Positive) is highly expensive, while rejecting a good borrower (False Negative) costs business. This pipeline heavily relies on:
* **Precision:** To ensure that loans predicted as "safe" are highly likely to be repaid.
* **Recall:** To capture as many actual qualified borrowers as possible.
* **F1-Score:** To maintain a robust harmonic balance between the two.

---
