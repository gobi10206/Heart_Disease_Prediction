# 🫀 Heart Disease Prediction using Logistic Regression

A machine learning classification project that predicts whether a patient has heart disease based on medical attributes and biomarkers.

---

## 📌 Overview

This project uses a **Logistic Regression** model built with Scikit-Learn to perform binary classification on cardiovascular health data. It loads patient records, splits them into stratified training and testing sets, trains the classifier, evaluates prediction accuracy, and provides a predictive system for new patient inputs.

---

## 📊 Dataset Information

* **Total Records:** 1,025 rows × 14 columns
* **Target Distribution:**
  * `1` (Heart Disease): 526 samples
  * `0` (Normal / Healthy): 499 samples
* **Missing Values:** None (0 null values across all columns)

### Clinical Features:
1. `age`: Patient age in years
2. `sex`: Biological sex (1 = male, 0 = female)
3. `cp`: Chest pain type (0–3)
4. `trestbps`: Resting blood pressure (mm Hg)
5. `chol`: Serum cholesterol in mg/dl
6. `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
7. `restecg`: Resting electrocardiographic results (0–2)
8. `thalach`: Maximum heart rate achieved
9. `exang`: Exercise-induced angina (1 = yes, 0 = no)
10. `oldpeak`: ST depression induced by exercise relative to rest
11. `slope`: The slope of the peak exercise ST segment (0–2)
12. `ca`: Number of major vessels (0–4) colored by fluoroscopy
13. `thal`: Thalassemia score (0–3)
14. **`target`**: Heart disease status (**0 = Healthy**, **1 = Heart Disease**)

---

## ⚙️ Project Setup & Installation

### 1. Requirements
Ensure you have Python installed along with the following libraries:

```bash
pip install numpy pandas scikit-learn
