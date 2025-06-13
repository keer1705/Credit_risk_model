# 💳 Credit Risk Classification Model

> A machine learning approach to predict whether a loan applicant is a **good** or **bad credit risk**—helping financial institutions make data-driven lending decisions.

This project leverages real-world financial data and advanced ML models to minimize defaults and optimize loan approvals.

---

## 📌 Table of Contents

- [🔍 Problem Statement](#-problem-statement)
- [📊 Dataset Overview](#-dataset-overview)
- [🧠 ML Pipeline](#-ml-pipeline)
- [🏁 Getting Started](#-getting-started)
- [📈 Model Evaluation](#-model-evaluation)
- [🚀 Future Improvements](#-future-improvements)
- [🙋‍♀️ Author](#-author)

---

## 🔍 Problem Statement

Credit risk assessment is critical in the banking and finance sector. Granting loans to high-risk applicants can result in significant losses.

This project addresses the challenge by:
- Predicting whether an applicant is likely to **repay** or **default**
- Reducing false negatives (approving risky applicants)
- Ensuring banks make **safer, smarter** decisions

---

## 📊 Dataset Overview

- **Dataset**: [UCI German Credit Data](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
- **Size**: 1,000 records
- **Features**: Credit history, loan amount, job status, duration, age, and more
- **Target Variable**:
  - `1` → Good credit risk (will repay)
  - `0` → Bad credit risk (likely to default)

---

## 🧠 ML Pipeline

### 🔄 Preprocessing
- Label Encoding & One-Hot Encoding
- Feature Scaling (StandardScaler)
- Handling imbalanced data (if needed)

### 🧪 Model Training
- **Train-Test Split** (80:20)
- Algorithms Used:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - **XGBoost** *(best performance)*

### 📊 Evaluation Metrics
- Confusion Matrix
- **Precision, Recall, F1-Score**
- **ROC AUC Score**

> 🎯 Focus: Maximizing **Recall** to minimize false negatives (default cases marked as safe).

---

## 🏁 Getting Started

### 🔧 Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries: `scikit-learn`, `xgboost`, `pandas`, `matplotlib`, `seaborn`

### 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/credit-risk-model.git
   cd credit-risk-model
