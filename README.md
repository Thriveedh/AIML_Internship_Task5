# AIML_Internship_Task5
# Heart Disease Prediction using Decision Tree and Random Forest

## Project Overview

This task aims to build machine learning models to predict the presence of heart disease based on patient clinical data. I used the **Heart Disease dataset** from Kaggle and applied classification algorithms such as **Decision Tree** and **Random Forest** to analyze and predict outcomes.

## Key Steps

### 1. Data Preprocessing and Outlier Removal
- Loaded the dataset containing various clinical features related to heart health.
- Identified numerical columns relevant for outlier detection.
- Removed outliers using the **Interquartile Range (IQR)** method to improve model robustness.

### 2. Feature Scaling
- Standardized numerical features using **StandardScaler** to ensure consistent scaling, which is crucial for many machine learning algorithms.

### 3. Model Training and Evaluation
- Split the data into training and testing sets.
- Trained a **Decision Tree Classifier** and controlled model complexity by tuning the tree depth to reduce overfitting.
- Trained a **Random Forest Classifier** and compared its performance with the Decision Tree.
- Evaluated models using accuracy, precision, recall, and f1-score metrics.
- Used **confusion matrices** to check for overfitting by comparing training and testing predictions.
- Applied **cross-validation** to obtain a more reliable estimate of model performance.

### 4. Feature Importance Analysis
- Extracted feature importances from the Random Forest model.
- Visualized which features contributed most to the prediction, aiding interpretability.

## Results Summary

- Random Forest achieved higher accuracy compared to the Decision Tree.
- Cross-validation confirmed the stability of the Random Forest model.
- Feature importance visualization identified key clinical indicators impacting heart disease prediction.
