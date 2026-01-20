# AI-ML-Task-4
AI & ML Internship: Task 4 

FEATURE ENCODING & SCALING

PROJECT DESCRIPTION

This project focuses on the Feature Engineering phase of the machine learning pipeline using the Adult Income Dataset. The goal is to transform raw data into a model-ready format by handling categorical variables and normalizing numerical scales.  

DATASET

Name: Adult Income Dataset  
Target Variable: Income (Predicting if income is >50K or <=50K)

WORKFLOW STEP TAKEN

Feature Identification: Categorized features into numerical and categorical types.  
Label Encoding: Applied to ordinal features (where a specific order exists, like education levels) to preserve their mathematical ranking.  
One-Hot Encoding: Applied to nominal features (where no order exists, like marital status or race) to prevent the model from assuming a hierarchy.  
Feature Scaling: Utilized StandardScaler on numerical features (Age, Hours-per-week, etc.) to transform them to have a mean of 0 and a standard deviation of 1.  
Model Readiness Comparison: Evaluated the dataset before and after preprocessing to ensure all features are on a comparable scale.

IMPACT OF SCALING ON ML ALGORITHMS

Scaling is essential for the following reasons:  
Distance-Based Algorithms: Models like KNN and SVM rely on calculating the distance between points. Without scaling, a feature with a large range (e.g., capital-gain) would dominate the distance calculation over a smaller feature (e.g., age).  
Gradient Descent: Scaling helps optimization algorithms converge faster, making training more efficient for models like Linear and Logistic Regression.
