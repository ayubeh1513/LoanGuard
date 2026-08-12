# 🛡️ LoanGuard: Credit Risk Assessment & Customer Segmentation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📌 Project Overview

**LoanGuard** is a Machine Learning based financial analytics project designed to analyze loan applicants, predict credit risk, estimate loan amount eligibility, and perform customer segmentation.

This project combines:

- 📈 **Regression** for Loan Amount Prediction
- ⚠️ **Classification** for Loan Default Risk Detection
- 👥 **Clustering** for Customer Segmentation
- 📊 **Exploratory Data Analysis (EDA)** for insights visualizations

The project demonstrates an end-to-end Machine Learning workflow including:

- Data preprocessing
- Missing value handling
- Label encoding
- Feature scaling
- Data visualization
- Model training
- Model evaluation
- Customer clustering
- PCA visualization

---

# 🚀 Features

✅ Data Cleaning & Preprocessing  
✅ Exploratory Data Analysis (EDA)  
✅ Loan Default Prediction  
✅ Loan Amount Prediction  
✅ Customer Segmentation using K-Means  
✅ Correlation Heatmaps & Visualizations  
✅ PCA-based Cluster Visualization  
✅ Accuracy & Evaluation Metrics  
✅ Business Insight Generation  

---

# 🧠 Machine Learning Models Used

| Model | Purpose |
|---|---|
| Linear Regression | Predict Loan Amount |
| Logistic Regression | Predict Loan Default Risk |
| K-Means Clustering | Customer Segmentation |
| PCA | Cluster Visualization |

---

# 📂 Dataset Features

The dataset contains customer financial and loan-related information such as:

- Applicant Income
- Loan Amount
- Credit History
- Loan Status
- Dependents
- Education
- Property Area
- Employment Status
- Marital Status
- Gender

---

# 📊 Exploratory Data Analysis (EDA)

The project includes several visualizations:

## 📌 Target Variable Distribution
- Pie Chart
- Count Plot

## 📌 Numerical Feature Distribution
- Histograms
- KDE Plots

## 📌 Feature vs Loan Status Analysis
- Boxplots
- Correlation Heatmaps

## 📌 Customer Segmentation Visualization
- Scatter Plots
- PCA Cluster Projection

---

# 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Language | Python |
| Notebook | Jupyter Notebook |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| ML Framework | Scikit-learn |
| Visualization | Matplotlib, Seaborn |

---

# 📦 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder, StandardScaler

from sklearn.linear_model import LinearRegression, LogisticRegression
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA

from sklearn.metrics import (
    accuracy_score,
    classification_report,
    confusion_matrix,
    mean_squared_error,
    r2_score
)
