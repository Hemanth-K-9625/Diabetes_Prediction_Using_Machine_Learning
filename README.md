# Diabetes Prediction using Machine Learning
## Overview
This project builds a machine learning model to predict whether a person has diabetes based on medical diagnostic measurements.
The goal of this project is to demonstrate the complete machine learning workflow including data preprocessing, exploratory data analysis, model training, hyperparameter tuning, and model evaluation.
---
## Dataset
The dataset used in this project is the **Pima Indians Diabetes Dataset**.
It contains medical data for female patients and includes the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable
Outcome:
- 0 → No Diabetes
- 1 → Diabetes

---

## Machine Learning Models Used

The following classification models were trained and evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
---

## Project Workflow

The project follows a complete machine learning pipeline:
1. Data Loading
2. Exploratory Data Analysis
3. Data Cleaning
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Hyperparameter Tuning using GridSearchCV
9. Model Comparison
10. Model Saving
---

## Model Evaluation

The models were evaluated using the following metrics:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
Hyperparameter tuning was performed to optimize model performance.

---

## Results

After comparing multiple models, ensemble methods such as Random Forest generally achieved strong performance on the dataset.
A comparison of model accuracy was performed before and after hyperparameter tuning.
---
## Project Structure

```
diabetes-prediction-ml/
│
├── notebook/
│   └── diabetes_prediction.ipynb
│
├── data/
│   └── diabetes.csv
│
├── models/
│   ├── logistic_regression.pkl
│   ├── decision_tree.pkl
│   ├── random_forest.pkl
│   └── svm.pkl
│
├── images/
│
├── requirements.txt
│
└── README.md
```
---
## Installation
Clone the repository:
```
git clone https://github.com/yourusername/diabetes-prediction-ml.git
```
Install dependencies:
```
pip install -r requirements.txt
```

---
## Running the Project

Open the notebook:
```
jupyter notebook notebook/diabetes_prediction.ipynb
```
Run all cells to reproduce the results.
---
## Future Improvements

Possible future improvements include:
- Training with larger medical datasets
- Using advanced models such as XGBoost
- Deploying the model using a web application
- Adding model explainability techniques

---

## Author
Hemanth Kumar
Computer Science Student interested in Data Science and Machine Learning.
