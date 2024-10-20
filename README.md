# Logistic-Reg-Titanic
# Logistic Regression Titanic Survival Prediction Project

## Project Overview
This project aims to predict the survival of passengers on the Titanic using a Logistic Regression model. The process includes data preprocessing, hyperparameter tuning, and feature engineering to enhance model performance.

## Steps
1. **Data Preprocessing**
    - We cleaned the dataset and prepared it for analysis by handling missing values, encoding categorical variables, and scaling features.
    - 2.1 Loading and getting an overview of the dataset
    - 2.2.1 Calculating coefficient for 'Age'
    - 2.2.2 Building Random Forest model for predicting 'Age' missing values
    
2. **Initial Model Training**
    - We trained an initial Logistic Regression model to establish a baseline performance.
    
3. **Hyperparameter Tuning**
    - We used GridSearchCV to fine-tune the hyperparameters ('C', 'penalty', 'solver') of our Logistic Regression model, optimizing for the ROC AUC score.
    - **Calculating:** 'C', 'Penalty', 'Solver', 'ROC AUC'
    
4. **Model Retraining**
    - Using the best hyperparameters, we retrained our Logistic Regression model and evaluated its performance.
    
5. **Feature Engineering**
    - We created new interaction features based on the most significant variables ('Pclass', 'Sex_male', 'Age'), converted them into dummy variables, and incorporated them into our model.
    - **Creating New Features**
    - **Retraining the Model with added features**
    
6. **Final Model Evaluation**
    - We retrained the model with the new features, achieving improved performance metrics.

## Conclusion
By systematically preprocessing the data, tuning hyperparameters, and engineering features, we successfully enhanced the performance of our Logistic Regression model. The final model demonstrates reliable accuracy and strong discriminative power, making it effective for predicting Titanic passenger survival.

## Authors
- ali.m.shafiei

## Acknowledgments
- Thanks to the Titanic dataset providers and scikit-learn library developers for their contributions.
