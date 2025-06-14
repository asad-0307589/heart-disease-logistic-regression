# Heart Disease Prediction using Logistic Regression

##  Task Objective
The primary goal of this task was to develop a machine learning model capable of predicting the presence of heart disease in patients based on clinical and demographic features. This project applies a supervised learning approach to classify individuals as either having heart disease (`target = 1`) or not (`target = 0`).

---

##  Dataset Used
- **Source:** UCI Machine Learning Repository – Heart Disease Dataset
- **Features Include:**
  - `age`, `sex`, `cp` (chest pain type), `trestbps` (resting blood pressure), `chol` (cholesterol), `fbs` (fasting blood sugar), `restecg` (resting ECG results), `thalach` (maximum heart rate achieved), `exang` (exercise-induced angina), `oldpeak`, `slope`, `ca`, `thal`, and `target`.
- **Target Variable:** `target` (0 = no heart disease, 1 = presence of heart disease)

---

##  Model Applied
- **Logistic Regression**
  - Preprocessing steps included encoding categorical variables (like `sex`, `cp`, `thal`), and handling missing values.
  - The dataset was split into training and test sets using an 80/20 split.
  - Model was trained with a maximum of 1000 iterations to ensure convergence.

---

## ✅ Key Results and Findings
- **Accuracy Achieved:** `0.82` (82%) on the test set.
- The logistic regression model demonstrated reliable performance on this binary classification task.
- The correlation heatmap helped identify the most influential features related to the target class.

---


