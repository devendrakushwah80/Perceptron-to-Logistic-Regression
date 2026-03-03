# Perceptron to Logistic Regression (From Scratch)

## 📌 Project Overview

This project demonstrates how a traditional Perceptron model can be transformed into Logistic Regression by modifying:

- Activation Function
- Learning Behavior (Loss Structure)

The implementation is built end-to-end including:

- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Histogram Visualization
- IQR-based Outlier Removal
- Custom Perceptron Implementation
- Logistic Regression via Activation Change
- Model Evaluation Metrics
- Cross Validation

---

## 🧠 Dataset

We use the Breast Cancer Wisconsin dataset from `sklearn.datasets`.

- Binary classification problem
- 30 numerical features
- Target: Malignant (0) / Benign (1)

---

## 🔎 Project Pipeline

1. Load Dataset
2. Perform EDA
   - Dataset shape
   - Summary statistics
   - Class distribution
3. Correlation Heatmap
4. Feature Histograms
5. IQR Outlier Filtering
6. Train-Test Split
7. Custom Perceptron Implementation
8. Convert to Logistic Regression
9. Model Evaluation
10. Cross Validation

---

## ⚙️ Model Design

### 🔹 Perceptron
- Linear decision boundary
- Step activation
- Hard classification

### 🔹 Logistic Regression (Modified Version)
Changes made:
- Step → Sigmoid activation
- Deterministic output → Probabilistic output

Mathematical change:

Perceptron:
    y = 1 if (w.x + b > 0) else 0

Logistic:
    y = sigmoid(w.x + b)

---

## 📊 Evaluation Metrics

The following metrics are used:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC AUC
- Cross Validation Accuracy

---

## 📈 Visualization Included

- Correlation Heatmap (Seaborn)
- Feature Histograms
- Class Distribution
- Confusion Matrix

---

## 🚀 Results

- Logistic Regression performs better due to probabilistic modeling.
- Cross-validation confirms model stability.
- Outlier removal improves performance consistency.

---

## 🏗 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🎯 Learning Outcome

This project demonstrates:

- Difference between Perceptron and Logistic Regression
- Importance of activation functions
- How loss behavior affects learning
- End-to-end ML workflow
- Building classifiers from scratch

---

## 👨‍💻 Author

Devendra Kushwah  
Machine Learning Enthusiast
