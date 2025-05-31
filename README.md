# Disease Prediction Using Machine Learning

This repository contains a machine learning project for disease diagnosis based on symptoms data. The goal is to predict diseases accurately using various classification algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, and Support Vector Machine (SVM).

---

## Project Overview

Healthcare professionals can benefit greatly from automated diagnostic tools. This project demonstrates how machine learning models can be trained on symptom data (binary encoded) to classify diseases with high accuracy.

---

## Dataset

- The dataset consists of 5000+ samples with symptoms represented as binary features (`0` or `1`).
- Each sample corresponds to a specific disease (target variable named `prognosis`).
- Each disease has at least 8 associated symptoms.
- Real-world diseases and their corresponding symptoms are used.

---

## Models Implemented

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**

Each model was trained, validated, and tested on the dataset. Performance metrics such as accuracy, precision, recall, F1-score, and confusion matrices were calculated and compared.

---

## Results Summary

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression  | 0.990    |
| K-Nearest Neighbors  | 0.989    |
| Random Forest       | 0.989    |
| Support Vector Machine (SVM) | 0.992    |

All models demonstrated excellent performance on this dataset, with SVM achieving the highest accuracy.

---

## Visualizations

Visual comparison of model accuracies is included using Matplotlib bar charts. Confusion matrices and detailed classification reports are also provided to analyze model performance.
