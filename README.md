# AIML-TASK4
# 🔍 Breast Cancer Classification using Logistic Regression

This project demonstrates how to build a *binary classification model* using *Logistic Regression* on the *Breast Cancer Wisconsin dataset. The objective is to predict whether a tumor is **malignant (0)* or *benign (1)* based on various diagnostic features.

---

## 🎯 Objective

- Apply logistic regression to a real-world classification task.
- Evaluate model performance using key classification metrics.
- Understand the role of the sigmoid function and classification threshold.

---

## 📁 Dataset

- *Source:* sklearn.datasets.load_breast_cancer()
- *Samples:* 569
- *Features:* 30 numeric features (e.g., mean radius, texture, symmetry)
- *Target:* 0 = malignant, 1 = benign

---

## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

---

## ✅ Steps Performed

### 1. Import and Prepare the Dataset
- Loaded dataset using sklearn.datasets
- Converted to a Pandas DataFrame
- Added target column

### 2. Train/Test Split and Standardization
- Split the data into *80% train* and *20% test*
- Standardized features using StandardScaler

### 3. Model Training
- Used LogisticRegression() from scikit-learn
- Fit the model on training data
- Made predictions on test data

### 4. Model Evaluation
- Evaluated using:
  - *Confusion Matrix*
  - *Precision*
  - *Recall*
  - *ROC Curve*
  - *AUC Score*
- Visualized performance using heatmaps and plots

### 5. Threshold Tuning & Sigmoid Function
- Adjusted classification threshold to observe effect on precision/recall
- Explained and visualized the *sigmoid function*, core to logistic regression
