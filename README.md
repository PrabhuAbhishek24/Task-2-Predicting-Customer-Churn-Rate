Project Overview
This project involves predicting customer churn rates using a machine learning model trained on the Churn_Modelling.csv dataset. The goal is to help stakeholders identify potential setbacks in the business by understanding factors contributing to customer churn. The project explores several statistical tools, including SHAP (Shapley Additive exPlanations) for model interpretability, as well as RandomSearch and GridSearch for hyperparameter tuning.

Features
Data Preprocessing: Clean and preprocess the dataset by handling missing values, encoding categorical variables, and standardizing features.
Model Training: Train a Random Forest Classifier to predict customer churn.
Hyperparameter Tuning: Use RandomSearch and GridSearch for optimizing model parameters.
Model Interpretation: Apply SHAP values to understand feature importance and model decisions.
Model Saving: Save the trained model as a .pkl file for future use.
File Structure
Churn_Modelling.csv: The dataset used for training the model.
churn_prediction.py: The main script containing the code for data preprocessing, model training, evaluation, and saving.
best_rf_model.pkl: The saved Random Forest model.
Usage
Run the script:

Ensure the Churn_Modelling.csv file is in the same directory as the script.
Execute the script to preprocess the data, train the model, perform hyperparameter tuning, and save the model.
Interpret the model:

SHAP summary and dependence plots are generated to visualize feature importance.
Results
The model’s performance is evaluated using confusion matrices, classification reports, and accuracy scores. SHAP values are used to explain which features most strongly influence the predictions.
