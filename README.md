# FraudGuard AI — Credit Card Fraud Detection using CNN & Deep Learning

## Overview

Financial fraud has become one of the biggest challenges in the banking and fintech industry. Traditional rule-based systems often fail to detect evolving fraud patterns in real time.

**FraudGuard AI** is a deep learning–powered fraud detection system designed to identify fraudulent credit card transactions using both classical Machine Learning algorithms and Convolutional Neural Networks (CNNs).

The project focuses on solving a real-world banking problem using AI-driven anomaly detection and predictive analytics techniques.

---

## Business Problem

Banks process millions of transactions every day. Even a small percentage of fraudulent transactions can lead to massive financial losses and reduced customer trust.

The challenge is difficult because:

* Fraudulent transactions are extremely rare
* Fraud patterns continuously evolve
* Real-world datasets are highly imbalanced
* False positives can negatively impact genuine users

This project aims to build an intelligent fraud detection pipeline capable of accurately identifying suspicious transactions while minimizing false alerts.

---

## Objective

The primary objective of this project is to:

* Detect fraudulent credit card transactions using AI/ML techniques
* Compare traditional Machine Learning models with Deep Learning approaches
* Evaluate model performance using real-world fraud detection metrics
* Build an industry-style fraud analysis workflow

---

# Models Implemented

## Classical Machine Learning Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gaussian Naive Bayes

## Deep Learning Models

* Artificial Neural Network (ANN)
* Convolutional Neural Network (CNN)

---

# Why CNN for Fraud Detection?

Although CNNs are traditionally used for image processing tasks, they can also learn hidden spatial feature relationships in structured financial datasets.

The CNN model in this project helps:

* identify complex fraud patterns,
* extract deep feature representations,
* improve anomaly detection capability,
* reduce manual feature engineering.

---

# Dataset Information

## Dataset Source

Kaggle — Credit Card Fraud Detection Dataset

## Dataset Statistics

* Total Transactions: 284,807
* Fraudulent Transactions: 492
* Fraud Ratio: 0.17%

## Features

* V1–V28 are PCA-transformed numerical features
* Time and Amount represent transaction metadata
* Class column:

  * 0 → Legitimate Transaction
  * 1 → Fraudulent Transaction

The dataset is highly imbalanced, making it suitable for real-world fraud detection experimentation.

---

# Project Pipeline

## 1. Data Preprocessing

* Missing value analysis
* Feature scaling
* Data normalization
* Train-test split

## 2. Exploratory Data Analysis (EDA)

* Fraud distribution visualization
* Correlation analysis
* Transaction pattern analysis
* Feature importance analysis

## 3. Model Training

Multiple Machine Learning and Deep Learning models were trained and evaluated.

## 4. Performance Evaluation

Models were compared using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 5. Fraud Prediction

The final system predicts whether a transaction is:

* Fraudulent
* Legitimate

---

# Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| CNN                 | 99.48%   |
| Decision Tree       | 99.62%   |
| Random Forest       | 99.30%   |
| Logistic Regression | 98.90%   |

---

# Tech Stack

## Programming Language

* Python 3.x

## Libraries & Frameworks

* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Development Environment

* Jupyter Notebook
* VS Code

---

# Project Structure

```bash
FraudGuard-AI/
│
├── notebooks/
│   ├── CNN_Fraud_Detection.ipynb
│   └── ML_Fraud_Detection.ipynb
│
├── dataset/
│
├── screenshots/
│
├── models/
│
├── requirements.txt
│
└── README.md
```

---

# How to Run the Project

## Step 1 — Clone Repository

```bash
git clone https://github.com/Utkarsh09513/FraudGuard-AI.git
```

## Step 2 — Install Dependencies

```bash
pip install -r requirements.txt
```

## Step 3 — Launch Jupyter Notebook

```bash
jupyter notebook
```

## Step 4 — Run the Notebooks

* Run `ML_Fraud_Detection.ipynb`
* Run `CNN_Fraud_Detection.ipynb`

---

# Future Improvements

* Real-time fraud detection pipeline
* Streamlit deployment dashboard
* Autoencoder-based anomaly detection
* Transformer-based financial modeling
* Hybrid CNN + LSTM architecture
* Real-time banking API integration

---

# Key Learnings

Through this project, I explored:

* Fraud analytics
* Deep Learning workflows
* CNN-based feature extraction
* Financial anomaly detection
* Model evaluation on imbalanced datasets
* Real-world AI applications in banking

---

# Author

## Utkarsha Singh

B.Tech Computer Science Engineering — 3rd Year
Bennett University

GitHub:
https://github.com/Utkarsh09513
