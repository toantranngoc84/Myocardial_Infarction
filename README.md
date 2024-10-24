# Myocardial Infaction - Heart Attack

## Overview

A heart attack, also known as myocardial infarction, is a medical emergency where the heart muscle begins to die because it isn’t receiving enough blood flow. This is typically caused by blockages in the arteries that supply blood to the heart. Without prompt medical intervention to restore blood flow, a heart attack can lead to permanent damage or death.
Early detection of the likelihood of a heart attack can help individuals seek timely medical advice.

## Features

### 1. **Dataset Information**
The dataset used for this project is sourced from [Mendeley](https://data.mendeley.com/datasets/wmhctcrt5v/1). It includes the following parameters:
- **Age**: Age of the patient.
- **Gender**: Male (1), Female (0).
- **Heart rate**: Heart rate in beats per minute (bpm).
- **Systolic blood pressure**: Systolic blood pressure in mmHg.
- **Diastolic blood pressure**: Diastolic blood pressure in mmHg.
- **Blood sugar**: Blood sugar level in mmol/L.
- **CK-MB**: Creatine Kinase MB in ng/mL.
- **Troponin**: Troponin levels in μg/L.
- **Result**: Positive (heart attack) or negative (no heart attack).

### 2. **Exploratory Data Analysis (EDA)**
At the beginning, the dataset was thoroughly examined:
- **Missing Values**: Checked and handled appropriately.
- **Outliers**: Analyzed and treated using visualizations.
- **Descriptive Statistics and Visualizations**: Used to gain insights into the distribution of data and to summarize the dataset.
- **Correlation Tests**: Applied to examine relationships between variables (Chi Square Test, Cramers V).

### 3. **Machine Learning Models**
This project compares a wide range of classification machine learning algorithms, which include:
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Used for handling class imbalance.
- **StandardScaler**: Applied for feature scaling and normalization.
- **Feature Selection Techniques**: 
  - Filter Methods: SelectKBest
  - Embedded Methods: L1 Regularization, L2 Regularization, Random Forest Importance
  - Wrappers Method: Recursive Feature Selection
- **Classification Base Models**:
  - Linear Model: Logistic Regression
  - Naive Bayes: Gaussian NB
  - Nearest Neighbors: K-Nearest Neighbors (KNN)
  - Decision Tree
  - Ensemble Methods: Random Forest, Gradient Boosting Machines
- **Boosting Models**: AdaBoost, Gradient Boosting, XGBoost
- **Hyperparameter Tuning**: Techniques like GridSearchCV and RandomizedSearchCV were used to optimize the models.
- **K-Fold Cross Validation**: Applied for reliable model evaluation.

### 4. **Model Evaluation**
The models are evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC Curve**

## Installation

To run this project locally on your machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/toantranngoc84/Myocardial_Infarction.git
   
2. **Navigate into the project directory:**:
   ```bash
   cd Myocardial_Infarction
   
3. **Install the required dependencies: Install the dependencies listed in the requirements.txt file:**:
   ```bash
   pip install -r requirements.txt
   
4. **Run the Jupyter Notebook: After installing the dependencies, open the Jupyter notebook by running:**:
   ```bash
   jupyter notebook heartattack.ipynb
   
5. **Clone the repository**:
   ```bash
   git clone https://github.com/toantranngoc84/Myocardial_Infarction.git
   
## Requirements

Below are the main Python packages required to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- imbalanced-learn
- xgboost

You can install these dependencies automatically using the provided `requirements.txt` file.

   
   
   
   
   
   
   
   
