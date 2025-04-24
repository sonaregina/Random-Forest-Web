# Random-Forest-Web

# REACTION – Breast Cancer Prediction from Medical Records

**REACTION** is a simple yet functional web-based application that predicts the likelihood of breast cancer using a Random Forest classification model. Built to demonstrate the practical use of machine learning in healthcare, the app allows users to input key medical data and receive instant prediction results.

---

## 💡 What It Does

This project takes 9 medical features related to metabolic health as input, processes them through a trained Random Forest model, and outputs a binary prediction: **Potential Risk** or **Low Risk** of breast cancer.

---

## 🔢 Features Used for Prediction

- Age
- BMI (Body Mass Index)
- Glucose Level
- Insulin Level
- HOMA (Insulin Resistance Score)
- Leptin
- Adiponectin
- Resistin
- MCP-1 (Monocyte Chemoattractant Protein)

These biomarkers are commonly found in medical records and have been linked to breast cancer risk in prior research.

---

## 🧠 Model Details

- **Algorithm:** Random Forest Classifier  
- **Library:** scikit-learn  
- **Language:** Python  
- **Training Dataset:** Tabular data with numeric biomarker scores  
- **Accuracy:** ~90% on test data

---

## 🖥️ Technologies

- **Frontend:** Basic HTML form (or Streamlit interface)
- **Backend/ML Model:** Python, pandas, scikit-learn
- **Deployment:** Localhost / Streamlit (if applicable)

---

## 🚀 How to Use

1. Click :
Run in Voila : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/azizahregina/Random-Forest-Web/main?urlpath=%2Fvoila%2Frender%2Fweb_randomforest.ipynb)

Run in Jupyter-Binder : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/azizahregina/Random-Forest-Web/main?filepath=web_randomforest.ipynb)

3. Enter values for each medical score.
4. Click the **Predict** button.
5. The system will return a prediction based on your inputs.

---

## 📌 Notes

This is a basic prototype to demonstrate the machine learning workflow. While simple in design, the model behind it is fully trained and tested on real-world data.

---

