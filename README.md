# Disease-Prediction-ML

4 Diseases Prediction (Brain Tumor, Heart Disease, Diabetes, Breast Cancer). A machine learning-based web application for predicting multiple diseases including Brain Tumor, Heart Disease, Diabetes, and Breast Cancer.

## 🎯 Project Overview

This project implements machine learning models to predict the likelihood of various critical diseases based on patient data and symptoms. The system currently supports prediction for:

- Brain Tumor
- Heart Disease
- Diabetes
- Breast Cancer

## 🚀 Features

- Multi-disease prediction capability
- User-friendly web interface
- Real-time prediction results
- Separate specialized models for each disease
- Comprehensive result analysis

## 💻 Technology Stack

- **Frontend**: HTML, CSS
- **Backend**: Python
- **Machine Learning Models**: 
  - `.h5` format for neural network models
  - `.pkl` format for traditional ML models
  - `.sav` format for some specific models

## 📂 Project Structure

```
Disease-Prediction-ML/
├── models/
│   ├── alzheimer_model.h5
│   ├── braintumor.h5
│   ├── cancer_model.pkl
│   ├── covid.h5
│   ├── diabetes.sav
│   ├── heart_disease.pickle.dat
│   └── pneumonia_model.h5
├── static/
├── templates/
│   ├── braintumor.html
│   ├── breastcancer.html
│   ├── diabetes.html
│   ├── heartdisease.html
│   ├── homepage.html
│   └── various result pages
├── app.py
├── LICENSE
└── README.md
```

## 🛠️ Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/username/Disease-Prediction-ML.git
cd Disease-Prediction-ML
```

2. Install required dependencies
```bash
pip install -r requirements.txt
```

3. Run the application
```bash
python app.py
```

## 🔍 Usage

1. Open the web application in your browser
2. Select the disease you want to predict
3. Input the required parameters/symptoms/scan report
4. Submit the form to get the prediction results
