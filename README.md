# Anomaly Detection for Fraud Detection

This project focuses on detecting fraudulent activities in financial transactions using machine learning techniques. It uses algorithms such as Isolation Forest and Local Outlier Factor (LOF) for unsupervised anomaly detection. Additionally, the project visualizes and analyzes the detected anomalies and evaluates the model’s performance using a confusion matrix.

## Overview
The goal of this project is to automatically detect fraud in financial data. We achieve this by applying anomaly detection techniques that are capable of identifying unusual patterns without prior knowledge of fraudulent activities.

## Key Features
  Data preprocessing including feature scaling and handling missing values.
  Anomaly detection using Isolation Forest and Local Outlier Factor (LOF).
  Visualization of anomalies with scatter plots, box plots, and KDE plots.
  Confusion matrix generation for evaluating model performance.

## Data Preprocessing
The dataset is cleaned and preprocessed to make it suitable for anomaly detection. The following steps are performed:

  Missing Value Handling: Missing values are either imputed with the mean or dropped.
  Feature Scaling: Numerical features are scaled using StandardScaler to ensure uniformity in feature distribution.
  Encoding Categorical Features: Categorical variables are one-hot encoded for analysis.

## Anomaly Detection Methods
### 1. Isolation Forest
Isolation Forest detects anomalies by isolating observations using random partitioning. It is particularly effective for high-dimensional data.
### 2. Local Outlier Factor (LOF)
LOF identifies anomalies by comparing the local density of a data point to its neighbors. A lower density relative to neighbors indicates an anomaly.
