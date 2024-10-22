# Titanic-Survived-Predicition
Titanic Survival Prediction Project
Overview
The Titanic Survival Prediction project aims to develop a machine learning model that predicts the survival of passengers aboard the Titanic based on various features from the dataset. Using Logistic Regression, the model identifies patterns in the data to classify passengers as either having survived or not.

Objectives
Analyze the Titanic dataset to extract meaningful insights.
Preprocess the data to handle missing values, encode categorical variables, and scale numeric features.
Build a Logistic Regression model to predict the likelihood of survival.
Evaluate the model's performance and fine-tune it for better accuracy.
Dataset
The dataset used in this project contains information about the passengers aboard the Titanic, including attributes such as:

Pclass: Passenger class (1st, 2nd, or 3rd)
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Fare: Fare paid by the passenger
Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
Survived: Survival status (0 = No, 1 = Yes)
Methodology
Data Preprocessing
Handling Missing Values:

Numeric columns are filled with the median value.
Categorical columns are filled with the most frequent value.
Encoding Categorical Variables:

Categorical variables are transformed using a Binary Encoder for better representation in the model.
Feature Scaling:

Numeric features are standardized using a Standard Scaler to ensure they contribute equally to the model's performance.
Model Development
Logistic Regression: The primary model used for binary classification tasks.
The model outputs the probability of survival, allowing for flexible decision-making based on varying thresholds.
Evaluation Metrics
Accuracy: The proportion of correct predictions made by the model.
ROC Curve and AUC: Tools used to assess the model's performance across different classification thresholds.
Usage
To use the model for predictions:

Preprocess new data using the provided transformation pipeline.
Make predictions using the trained Logistic Regression model.
Adjust the classification threshold as necessary based on the project requirements.

Conclusion
The Titanic Survival Prediction project demonstrates the power of machine learning in analyzing historical data and making informed predictions. By leveraging Logistic Regression, the project provides a foundation for further exploration of more complex models and feature engineering techniques. This project serves as an educational tool for understanding the machine learning pipeline from data preprocessing to model evaluation.

Future Work
Explore more advanced models (e.g., Random Forest, Gradient Boosting) for improved accuracy.
Perform hyperparameter tuning to optimize model performance.
Conduct feature importance analysis to identify the most impactful features influencing survival.
