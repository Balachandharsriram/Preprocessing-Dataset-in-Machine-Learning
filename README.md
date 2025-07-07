# Preprocessing-Dataset-in-Machine-Learning
Using a Random Dataset into Preprocessing
# 🚀 Employee Data Preprocessing Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Dataframe-green?style=flat-square&logo=pandas)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-purple.svg?style=flat-square)

---

## 🎯 Project Overview

This repository contains a **comprehensive preprocessing pipeline** applied on an Employee dataset.  
It tackles **missing values, outliers, encoding, and scaling**, ensuring your data is ML-ready 🚀.

---

## 📂 Key Features

✨ **Data Loading & Exploration**
- Imported CSV data into a pandas dataframe.
- Explored dataset shape, types, and summary.

🧩 **Handling Missing Data**
- Visualized with `missingno` bar & matrix plots.
- Heatmaps to explore patterns.
- Filled missing:
  - Age → Mean
  - Salary → Median
  - Gender → Mode
- Alternative using `SimpleImputer`.

🚨 **Outlier Detection & Handling**
- Used **IQR method** & **Z-score**.
- Isolation Forest to detect multivariate anomalies.
- Replaced outliers with median.

📝 **Encoding Categorical Data**
- `LabelEncoder` for binary `Gender`.
- `get_dummies` for multi-class `Department`.
- `OneHotEncoder` demo.

⚖️ **Feature Scaling**
- `StandardScaler` for standardization (Age).
- `MinMaxScaler` for normalization (Salary).

📊 **Data Visualization**
- Boxplots for outliers.
- Scatter plots for relationships.

---

## 🔥 Screenshots

<p align="center">
  <img src="screenshots/missingno_bar.png" width="400" alt="Missingno Bar Plot">
  <img src="screenshots/boxplot_age.png" width="400" alt="Boxplot of Age">
</p>

---

## 🚀 Getting Started

### 🔧 Prerequisites

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn missingno scikit-learn
🏃 Running the Notebook
bash
Copy
Edit
jupyter notebook
Open Preprocessing.ipynb and execute cells step by step.

🛠 Tech Stack
Library	Usage
pandas	Data manipulation
numpy	Numerical calculations
matplotlib	Plotting
seaborn	Statistical plots
missingno	Missing value visualization
scikit-learn	Encoding, scaling, outlier detection

🚀 Why use this notebook?
✅ Build robust preprocessing pipelines for machine learning.
✅ Easy to adapt for customer, healthcare, finance, or HR datasets.
✅ Visual diagnostics for data quality issues.

👨‍💻 Author
Balachandharsriram M

💌 Open to feedback, contributions, and collaborations!


