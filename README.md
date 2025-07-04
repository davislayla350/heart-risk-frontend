#  Heart Disease Risk Predictor

This project is a web-based tool that allows users to assess their potential risk of heart disease based on medical indicators such as age, cholesterol, chest pain type, and more. It uses a trained machine learning model on health data to provide a simple "High Risk" or "Low Risk" prediction.

>  This tool is for educational purposes only and is not a medical diagnostic service. Always consult a healthcare provider for real medical advice.

---

## Live Demo

**Frontend:** [https://davislayla350.github.io/heart-risk-frontend/](https://davislayla350.github.io/heart-risk-frontend/)  
**Backend API:** [https://heart-risk-api.onrender.com](https://heart-risk-api.onrender.com)

---

## Model Information

The model was trained using a **Random Forest Classifier** on the [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).  
It was preprocessed and serialized (`.pkl`) using **scikit-learn**.

---

## Tech Stack

**Frontend:**
- HTML5 + CSS (Tailwind via CDN)
- Vanilla JavaScript
- GitHub Pages for hosting

**Backend:**
- Python 3.10+
- FastAPI
- joblib (for loading the ML model)
- Render (for live deployment)

---

## Credits
Dataset: Heart Disease Prediction (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

Model: Trained in Python using scikit-learn

UI inspired by modern accessibility principles

