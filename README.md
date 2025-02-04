# Heart Disease Dataset - Indians

## Overview
This repository contains two datasets related to heart disease in the Indian population. The datasets include various health parameters such as BMI, smoking habits, physical activity, hypertension, diabetes, cholesterol levels, and other lifestyle factors. The goal is to analyze these factors and predict the likelihood of heart disease.

## Datasets
### 1. Training Dataset (`heart_disease_train.csv`)
Download: https://drive.google.com/file/d/1cu2wzcCqz6jORDfvXyBznfau2e19IyD7/view?usp=drive_link
- **Size:** 75 records
- **Purpose:** Used for training machine learning models to predict heart disease
- **Target Column:** `Heart_Disease` (0: No, 1: Yes)
- **Columns:**
  - `Age` (int): Age of the individual (30-80 years)
  - `Gender` (str): Male/Female
  - `BMI` (float): Body Mass Index (18.0 - 35.0)
  - `Smoking` (int): 0 - No, 1 - Yes
  - `Alcohol` (int): 0 - No, 1 - Yes
  - `Physical_Activity` (str): Low, Moderate, High
  - `Hypertension` (int): 0 - No, 1 - Yes
  - `Diabetes` (int): 0 - No, 1 - Yes
  - `Cholesterol` (str): Normal, Borderline, High
  - `Family_History` (int): 0 - No, 1 - Yes
  - `Stress_Levels` (str): Low, Medium, High
  - `Diet_Type` (str): Vegetarian, Non-Vegetarian, Mixed
  - `Sleep_Hours` (float): Hours of sleep per day (4-9 hours)
  - `Heart_Rate` (int): Heart rate in beats per minute (60-120)
  - `Blood_Pressure` (str): Systolic/Diastolic (e.g., 120/80)
  - `Heart_Disease` (int): 0 - No, 1 - Yes (Target Variable)

### 2. Testing Dataset (`heart_disease_test.csv`)
Download: https://drive.google.com/file/d/1rnunS1nVgHIj2CXuThdLAN3Em_SlS-Yj/view?usp=drive_link
- **Size:** 15 records
- **Purpose:** Used for making predictions based on trained models
- **Target Column:** `Heart_Disease` (Left empty for predictions)
- **Columns:** Same as the training dataset, except `Heart_Disease` is left blank.

## Usage
1. Use the training dataset to build and train a classification model for predicting heart disease.
2. Use the testing dataset to evaluate the model's performance by predicting `Heart_Disease` values.
3. Analyze the relationships between different factors and their impact on heart disease prevalence.

## Potential Applications
- Healthcare analytics and early prediction of heart disease risk.
- Preventive health measures based on lifestyle and medical history.
- Research studies on heart disease prevalence in the Indian population.

## License
This dataset is provided for research and educational purposes only.

## Contact
For any queries or suggestions, feel free to reach out.

---
**Author:** Generated using synthetic data for research and model training purposes.
