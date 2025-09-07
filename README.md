# HR Analytics Attrition Prediction

## Table of Contents
- [Introduction](#introduction)  
- [Dataset Overview](#dataset-overview)  
- [Python Libraries Used](#python-libraries-used)  
- [Project Workflow](#project-workflow)  
- [Purpose of the Analysis](#purpose-of-the-analysis)  

---

## Introduction
Employee attrition is a significant challenge for organizations, resulting in increased recruitment costs and potential loss of talent.  
This project uses **machine learning** techniques to predict employee attrition and provides insights into the factors influencing employees' decisions to leave the company.  

---

## Dataset Overview
The dataset used is the **IBM HR Analytics Employee Attrition & Performance** dataset.  
It contains information about employees, including their demographics, job roles, performance ratings, and other attributes.  

- **Number of instances:** 1,470  
- **Number of attributes:** 35  
- **Target variable:** `Attrition` (Yes/No)  

This dataset helps in analyzing the key factors affecting employee attrition and predicting future resignations.

---

## Python Libraries Used
The following Python libraries were utilized in this project:  

- `pandas` – Data manipulation and analysis  
- `numpy` – Numerical computations  
- `matplotlib.pyplot` – Data visualization  
- `seaborn` – Statistical data visualization  
- `scikit-learn` – Machine learning algorithms and tools  
- `shap` – Model interpretability  

---

## Project Workflow

1. **Import Libraries** – Load essential Python libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn.  
2. **Load Dataset** – Read the HR Analytics dataset and inspect the data.  
3. **Data Exploration** – Check data types, summary statistics, and target variable distribution.  
4. **Data Cleaning & Preprocessing** – Handle missing values, encode categorical variables, and scale numerical features.  
5. **Feature Engineering** – Create derived features and remove irrelevant columns.  
6. **Exploratory Data Analysis (EDA)** – Visualize distributions, correlations, and relationships with the target variable.  
7. **Train/Test Split & Model Building** – Split data, build baseline and advanced machine learning models.  
8. **Model Evaluation** – Evaluate using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.  
9. **Model Interpretation** – Use SHAP to identify key factors influencing attrition.  
10. **Conclusion & Insights** – Summarize findings and provide actionable HR recommendations.

---

## Purpose of the Analysis

The main goals of this analysis are:  

- **Predict Employee Attrition** – Build a model to forecast which employees are likely to leave.  
- **Identify Key Factors** – Understand the most significant features influencing attrition.  
- **Provide Insights** – Help HR departments implement strategies to improve employee retention.  

---

## 📊 Key Results  
- **Best Model**: Tuned Random Forest Classifier  
- **Accuracy**: ~87%  
- **Precision**: ~84% | **Recall**: ~81% | **F1-Score**: ~82%  
- **Top Features**: Overtime, Monthly Income, Years at Company, Job Satisfaction, Age  

---

