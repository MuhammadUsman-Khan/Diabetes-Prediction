# Diabetes Prediction ML Model 🩺🤖

## Overview 📋

This project implements a **Machine Learning model** to predict whether a person has diabetes based on diagnostic measurements. It leverages the **PIMA Diabetes dataset** with 768 samples and 8 key health features.

---

## Dataset Details 🗃️

* Rows: 768

* Columns: 9 (8 features + 1 outcome)

* Features include:

* Pregnancies

* Glucose

* Blood Pressure

* Skin Thickness

* Insulin

* BMI

* Diabetes Pedigree Function

* Age

* Target: Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## Data Exploration & Insights 🔍

* The dataset shows an imbalance with 500 non-diabetic and 268 diabetic cases.

* Diabetic patients tend to have higher average glucose, BMI, and age values.

* Some features have zeroes which likely represent missing data and were standardized in preprocessing.

---

## Preprocessing Steps 🧹

* Standardized all feature values using StandardScaler to normalize the range and improve model performance.

* Split data into training (80%) and testing (20%) sets, maintaining the original class distribution (stratification).

---

## Model Development 🏗️

* Trained a Support Vector Machine (SVM) classifier with a linear kernel on the training data.

* Evaluated accuracy on both training and test datasets.

---

## Performance Metrics 📊

* Training Accuracy: ~78.66%

* Testing Accuracy: ~77.27%

* These results demonstrate good generalization and reliable predictive capability.

---

## Predictive System Demo 💡

* Provided a sample input to predict diabetes status.

* The system standardizes the input data and outputs whether the individual is diabetic or not.

---

## Use Cases & Impact 🌟

* Supports early detection of diabetes for better medical intervention.

* Assists healthcare providers in risk assessment based on common medical measurements.

* Can be extended to a user-friendly app or clinical tool.

---

## Future Enhancements 🚀

* Handle missing data more robustly to improve model accuracy.

* Experiment with ensemble models and hyperparameter tuning.

* Deploy as a web service or integrate with wearable health devices for real-time monitoring.

