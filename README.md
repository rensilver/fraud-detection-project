# Credit Card Fraud Detection Using Isolation Forest

## Overview

This project focuses on detecting fraudulent credit card transactions using anomaly detection techniques.

Fraudulent transactions are extremely rare compared to normal transactions, making this a highly imbalanced classification problem. To address this challenge, this project uses the Isolation Forest algorithm, which is specifically designed for anomaly detection.

The project demonstrates a complete machine learning workflow including:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature scaling
* Anomaly detection modeling
* Model evaluation

---

# Business Problem

Financial institutions lose millions of dollars every year due to fraudulent transactions.

Because fraud patterns constantly evolve and fraud cases are rare, traditional rule-based systems may fail to detect suspicious activities effectively.

The goal of this project is to identify potentially fraudulent transactions automatically using machine learning anomaly detection techniques.

---

# Dataset

Dataset used:

* [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### Dataset Information

* 284,807 transactions
* 492 fraudulent transactions
* Highly imbalanced dataset
* Numerical features only
* Real anonymized credit card transaction data

### Target Variable

| Class | Meaning                |
| ----- | ---------------------- |
| 0     | Normal transaction     |
| 1     | Fraudulent transaction |

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Exploratory Data Analysis (EDA)

The exploratory analysis included:

* Dataset shape analysis
* Missing value inspection
* Class imbalance analysis
* Transaction amount distribution
* Correlation analysis

### Visualizations

* Fraud vs Non-Fraud distribution
* Transaction amount histogram
* Correlation heatmap
* Confusion matrix heatmap

---

# Data Preparation

## Feature Scaling

The following features were scaled:

* `Amount`
* `Time`

Scaling was performed using:

* `StandardScaler`
* `RobustScaler`

---

# Model

## Isolation Forest

This project uses the Isolation Forest algorithm for anomaly detection.

### Why Isolation Forest?

* Fast training
* Designed for anomaly detection
* Works well with imbalanced datasets
* Easy to explain
* Effective for tabular financial data

---

# Model Evaluation

The model was evaluated using:

* Precision
* Recall
* Confusion Matrix
* Classification Report

### Why These Metrics?

In fraud detection, accuracy alone is not enough because the dataset is highly imbalanced.

The project focuses mainly on:

* **Recall** → ability to detect fraud cases
* **Precision** → reliability of fraud predictions

---

# Results

Expected model behavior:

* High recall
* Moderate precision
* More importance on detecting fraud than maximizing accuracy

This behavior is common in anomaly detection systems.

---

# Learning Outcomes

This project demonstrates:

* Real-world machine learning workflow
* Handling imbalanced datasets
* Anomaly detection techniques
* Data preprocessing
* Model evaluation

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/fraud-detection-project.git
```

Run the notebook:

```bash
jupyter notebook
```

---

# Author

Renato Silveira
