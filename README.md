# 🛡️ Car Insurance Claim Prediction – No-Code ML with KNIME

A visual data science project that uses **KNIME Analytics Platform** to predict whether a customer will file a car insurance claim. This workflow helps insurance companies minimize risk and detect potential fraud by leveraging predictive analytics — no coding required!

---

## 🎯 Objective

Use customer, vehicle, and policy data to build a classification model that predicts the likelihood of a car insurance claim being made.

---

## ⚙️ Workflow Overview

This KNIME-based workflow includes the following steps:

1. **Data Import** – Load insurance dataset (.csv format)
2. **Preprocessing** – Handle missing values, encode categorical variables
3. **Feature Selection** – Correlation analysis to identify key predictors
4. **Modeling** – Build and compare classification models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
5. **Evaluation** – Accuracy, confusion matrix, ROC curve
6. **Deployment Ready Output** – Export predictions & model scores

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **KNIME** | No-code ML workflow design |
| **CSV Dataset** | Input data |
| **Classification Learner & Predictor** | Machine learning models |
| **Scorer Node** | Evaluate performance |
| **ROC Curve / Confusion Matrix** | Model visualization |

---

## 🗂️ Project Structure

```bash
car-claim-prediction-knime/
├── claim_prediction.knwf           # KNIME workflow file
├── insurance_data.csv              # Input dataset
├── screenshots/
│   ├── workflow_layout.png
│   ├── confusion_matrix.png
└── README.md
