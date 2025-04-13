# Breast-Cancer-Capstone-Project
## Breast Cancer Prediction using Machine Learning
This project demonstrates various machine learning techniques using the Wisconsin Breast Cancer dataset. The analysis includes data cleaning, Exploratory Data Analysis (EDA), feature engineering, and the implementation of several machine learning models for cancer prediction. The model could serve as a useful tool for supporting medical diagnosis.

## Dataset
The Wisconsin Breast Cancer dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image. The target variable classifies tumors as either malignant or benign. 

## Analysis Overview
The project covered:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering and selection
- Model selection and evaluation
- Hyperparameter tuning
- Model interpretation

## Models Implemented
- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Random Forest
- Gradient Boosting

## Results: 
Model Performance:
   - The logistic regression model achieved high accuracy in predicting breast cancer
   - The ROC curve and AUC score indicate great discriminative ability

Feature Importance:
   - The most important features for prediction are shown below in the order of importance, which can be useful for medical professionals:
      * worst texture    1.350606
      * radius error    1.268178
      * worst symmetry    1.20820
      * mean concave points    1.119804
      * worst concavity    0.943053
      * area error    0.907186
      * worst radius    0.879840
      * worst area    0.841846
      * mean concavity    0.801458
      * worst concave points    0.778217

Clinical Implications:
   - The model could serve as a useful tool for supporting medical diagnosis
   - High accuracy in both malignant and benign cases suggests reliable predictions
   - Important features identified could guide future medical research
