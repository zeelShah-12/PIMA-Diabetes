# PIMA-Diabetes
# 🩺 Diabetes Prediction with Machine Learning

This project predicts whether a person is likely to have diabetes based on medical attributes, using a trained machine learning model and a simple web interface built with Gradio.

---

## 📌 Overview

- Built with **Python**, **scikit-learn**, and **Gradio**
- Trained on the **Pima Indians Diabetes Dataset**
- Deploys a prediction app with clean inputs and outputs
- Ideal for beginners/intermediate ML learners

---

## 📁 Dataset

- Source: [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features used for prediction:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- Label: `0 = Not Diabetic`, `1 = Diabetic`

---
## 🧪 Example Prediction

**Input:**

| Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin | BMI  | DPF  | Age |
|-------------|---------|----------------|----------------|---------|------|------|-----|
| 6           | 160     | 70             | 30             | 200     | 35.0 | 0.7  | 50  |

**Output:**

Prediction: Diabetic

## 🚀 How to Use

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/yourusername/diabetes-predictor.git
cd diabetes-predictor

