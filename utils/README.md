# Predicting Myocardial Infarction using Supervised Machine Learning

## Overview

This project aims to predict the likelihood of myocardial infarction (heart attack) using supervised machine learning techniques. The dataset, collected from Zheen Hospital, Erbil, Iraq, includes various patient health indicators. The final model will be deployed as an interactive web application using Streamlit.

## Project Structure

1. **Medical Study**
   - **Institution:** Zheen Hospital, Private hospital and heart center located in Erbil, Iraq.
   - **Study Period:** January to May 2019.
   - **Sample Size:** 1319 patients.
   - **Dataset Features:** Age, gender, heart rate, systolic and diastolic blood pressure, blood sugar, CK-MB, troponin, and heart attack occurrence.
   - **Objective:** Predict heart disease in native patients.

2. **Myocardial Infarction**
   - **Definition:** A heart attack (myocardial infarction) occurs when blood flow to the heart muscle is severely reduced or blocked.
   - **Causes:** Typically due to blockage in one or more of the heart's arteries.
   - **Consequences:** Without prompt treatment, the affected heart muscle can start to die, leading to potential permanent damage or death.
   - **Symptoms:** Chest pain, radiation of pain, shortness of breath, nausea, sweating.

3. **Biomarkers**
   - **CK-MB:** A specific form of creatine kinase found in heart muscle, released into the blood when there is damage to the heart muscle.
   - **Troponin:** Cardiac troponins (Troponin T and Troponin I) are proteins present in the muscle cells of the heart that increase in the bloodstream after heart muscle damage.

4. **Exploratory Data Analysis (EDA)**
   - Perform EDA to understand the dataset, identify patterns, and visualize relationships between features.

5. **Feature Analysis**
   - Analyze the importance and correlation of various features to the target variable (heart attack occurrence).

6. **Supervised Machine Learning**
   - **Task:** Classification.
   - **Data Handling:** Train, validate, and test split, SMOTE for handling class imbalance, standard scaling.
   - **Feature Selection Models:** L1 Regularization, L2 Regularization, Random Forest Importance, Recursive Feature Selection, SelectKBest (ANOVA).
   - **Base Models:** Logistic Regression, Gaussian NB, KNN, Decision Tree, Random Forest, Gradient Boost Machines.
   - **Hyperparameter Tuning:** Grid Search, Random Search.
   - **Boosting Models:** AdaBoost, Gradient Boosting, XGBoost.

7. **Results**
   - **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score, ROC-AUC.
   - **Best Models:** Decision Tree, Random Forest + Gradient Booster, Neural Networks, Support Vector Machines + AdaBoost, Logistic Regression + AdaBoost.
   - **Performance:** Metrics for each model configuration.

8. **Streamlit App**
   - **Features:**
     - Video about heart attack.
     - Map of the hospital.
     - Educational content on heart attack signs, symptoms, and risk factors.
     - Interactive statistics with filter functions (gender, age group).
     - Machine Learning Prediction: Users can input features (gender, age, heart rate, etc.) to get the probability of a heart attack.
   - **Prevention Information:** Tips on how to lower the risk of a heart attack.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/heart-attack-prediction.git
   cd heart-attack-prediction
