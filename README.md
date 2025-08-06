# Diabetes Prediction using Machine Learning

This project investigates the effectiveness of classical machine learning models in predicting diabetes based on patient health indicators from the Pima Indians Diabetes dataset. It involves data preprocessing, exploratory data analysis, and model evaluation using logistic regression and random forest classifiers. The goal is to build a simple, interpretable, and accurate predictive pipeline for binary classification of diabetes presence.

---

---

## 📂 Project Structure

```
Diabetes-ML-Project/
├── PimaIndiansDiabetes.csv       # Original dataset
├── ProjektML_Final.ipynb         # Jupyter notebook with full analysis
├── requirements.txt              # Python dependencies
└── .gitignore                    # Git ignored files
```

---

## ⚙️ Installation

Clone the repository:

```powershell
git clone https://github.com/your-username/Diabetes-ML-Project.git
cd Diabetes-ML-Project
```

Create a virtual environment and install dependencies:

```powershell
python -m venv venv
.\venv\Scripts\activate.ps1
pip install -r requirements.txt
```

---

## 🧪 Notebook Overview

- Loads and explores the dataset
- Cleans and preprocesses data (e.g., handling zero values, scaling)
- Splits data into train/test sets
- Trains and evaluates multiple machine learning models
- Presents results using accuracy scores and confusion matrices

---

## 📊 Dataset Information

- Source: Pima Indians Diabetes Dataset on Kaggle
- Samples: 768
- Features:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- Target: Outcome (1 = diabetes, 0 = no diabetes)

---

## 🧠 Modeling Approach
The project uses:
  - Exploratory Data Analysis to understand feature relationships
  - Data scaling (StandardScaler) to normalize input features
  - Classical ML models:
    - Logistic Regression: For baseline binary classification
    - Random Forest Classifier: For improved accuracy and feature importance insights
  - Model evaluation using:
    - Accuracy Score
    - Confusion Matrix
    - Classification Report

---

## 📦 Requirements

See `requirements.txt` for a full list of dependencies, including:
- pandas
- numpy
- scikit-learn
- matplotlib, seaborn
- jupyter

---

## 👥 Author: Filip Urbaniak

---
