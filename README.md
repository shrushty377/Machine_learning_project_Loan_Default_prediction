# Loan Default Prediction – Machine Learning Project

## 📖 Overview
This project aims to predict loan default status using machine learning classification techniques. The dataset contains both numerical and categorical features related to loan applicants, requiring thorough preprocessing before model training.

The solution follows an end-to-end ML pipeline, starting from data cleaning and feature encoding to model evaluation and final prediction generation.

---

## 🎯 Problem Statement
Financial institutions face significant risk when approving loans. The goal of this project is to predict whether a customer will default on a loan, helping lenders make informed decisions and reduce potential losses.

---

## 🧠 Machine Learning Approach
- Problem Type: **Binary Classification**
- Target Variable: **Loan Default (Yes / No)**
- Evaluation Metrics:
  - Precision
  - Recall
  - F1-score
  - Accuracy

---

## 🗂️ Project Workflow

1. **Data Loading**
   - Importing dataset
   - Initial inspection and understanding

2. **Data Preprocessing**
   - Handling missing values
   - Converting data types
   - Encoding categorical variables
   - Feature scaling

3. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions
   - Identifying imbalance in target classes

4. **Train-Test Split**
   - Separating data into training and testing sets

5. **Class Imbalance Handling**
   - Upsampling minority class to improve model performance

6. **Model Building**
   - Baseline models
   - Random Forest Classifier

7. **Hyperparameter Tuning**
   - GridSearchCV for optimal parameters
   - Performance comparison before and after tuning

8. **Model Evaluation**
   - Classification report
   - Comparison of baseline vs tuned model

9. **Final Predictions**
   - Generating predictions on test data
   - Creating `submission.csv` file

---

## 📊 Models Used
- Random Forest Classifier (Baseline)
- Tuned Random Forest (Best Model)

---



