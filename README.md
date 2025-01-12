# Heart Disease Prediction

This repository contains a web-based application for predicting heart disease using machine learning models. The application leverages the power of three advanced machine learning algorithms:

- **XGBoost**
- **LightGBM**
- **Random Forest**

## Input Parameters
The application accepts the following inputs:

1. **Age**: Age of the patient.
2. **Sex**: Gender of the patient (Male/Female).
3. **Chest Pain Type (CP)**:
   - Typical Angina
   - Atypical Angina
   - Non-Anginal Pain
   - Asymptomatic
4. **Resting Blood Pressure (Trestbps)**: Resting blood pressure in mm Hg.
5. **Cholesterol Level (Chol)**: Serum cholesterol in mg/dL.
6. **Fasting Blood Sugar (FBS)**: Whether fasting blood sugar > 120 mg/dL (Yes/No).
7. **Resting ECG (Restecg)**:
   - Normal
   - Mild Abnormality
   - Serious Abnormality
8. **Heart Rate Achieved (Thalach)**: Maximum heart rate achieved.
9. **Exercise Induced Angina (Exang)**: Presence of exercise-induced angina (Yes/No).
10. **Oldpeak**: ST depression induced by exercise relative to rest.
11. **Slope**: Slope of the peak exercise ST segment (Up/Flat/Down).
12. **CA**: Number of major vessels colored by fluoroscopy (0-3).
13. **Thalassemia (Thal)**:
    - No Defect
    - Normal
    - Fixed Defect
    - Reversible Defect

---

## Dataset

The models were trained on a heart disease dataset containing various clinical parameters. You can download a similar dataset from [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

---

## Acknowledgments
- Developers of XGBoost, LightGBM, and Random Forest for their amazing libraries.


