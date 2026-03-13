# TS-academy-4
 Diabetes prediction using Logistic Regression on the  Diabetes Dataset. Includes EDA, data preprocessing, and model evaluation with Accuracy,  and Confusion Matrix.
 
#  Diabetes Prediction — Logistic Regression

## Overview
This project builds a Logistic Regression model to predict whether a
patient has diabetes based on diagnostic measurements. Using the Diabetes Dataset, the model classifies patients as diabetic (1) or non-diabetic (0) based on 8 medical features.

---

## 📂 Dataset
- **Source:**  Diabetes Dataset
- **Rows:** 768 patients
- **Features:** 8 input features + 1 target variable

| Column | Description | Type |
|---|---|---|
| `Pregnancies` | Number of times pregnant | int64 |
| `Glucose` | Plasma glucose concentration | int64 |
| `BloodPressure` | Diastolic blood pressure (mm Hg) | int64 |
| `SkinThickness` | Triceps skin fold thickness (mm) | int64 |
| `Insulin` | 2-Hour serum insulin (mu U/ml) | int64 |
| `BMI` | Body mass index (weight in kg / height in m²) | float64 |
| `DiabetesPedigreeFunction` | Diabetes likelihood based on family history | float64 |
| `Age` | Age of patient (years) | int64 |
| `Outcome` | **Target** — 1 = Diabetic, 0 = Non-Diabetic | int64 |

---

## Objectives
- Explore and understand the distribution of medical features
- Handle missing values
- Build a Logistic Regression model to classify patients
- Evaluate model performance using classification metrics
- Analyse the relationship between features and diabetes outcome

---

##  Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Logistic Regression & evaluation metrics |
| Jupyter Notebook | Development environment |

---

##  Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
- Distribution of all medical features
- Class balance check (Diabetic vs Non-Diabetic)
- Correlation heatmap
- Feature distributions by Outcome

### 2. Data Preprocessing
- Handling zero values in medical columns
  (Glucose, BloodPressure, SkinThickness, Insulin, BMI)
- Feature scaling / standardisation
- Train/Test split (80% train / 20% test)

### 3. Model Building
- Logistic Regression with Scikit-learn
- Model training and prediction

### 4. Model Evaluation
- Accuracy Score
- Confusion Matrix

---

## Results
| Metric | Score |
|---|---|
| Accuracy | 0.7013|

---


## 🔮 Future Work
- Try other classification models (Random Forest, SVM, XGBoost)
- Handle zero values more rigorously with imputation
- Perform feature selection to improve model performance
- Hyperparameter tuning with GridSearchCV
- Deploy model as a web app using Flask or Streamlit

---

