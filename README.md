# Predicting-Customer-Churn-in-a-Telecom-Company
This project analyzes a telecom customer dataset to predict churn using machine learning models. Key customer attributes, such as tenure and monthly charges, are visualized to identify patterns. Logistic Regression and Random Forest classifiers are applied to predict churn, aiming to improve customer retention strategies.




# Telecom Customer Churn Prediction Project

## Overview
This project aims to predict customer churn in a telecom company using machine learning models. The dataset contains customer data, including their behavior, services used, and whether they churned (left the service). We use this information to build models that can help predict which customers are likely to churn.

## Dataset
- The dataset for this project is provided by the professor, and it includes various customer attributes like tenure, services used, and monthly charges.
- The target variable is whether a customer has churned or not.

## Machine Learning Models
In this project, we use two machine-learning models to predict customer churn:
- **Logistic Regression**: A classification algorithm suitable for binary outcomes like churn prediction.
- **Random Forest Classifier**: An ensemble learning method that operates by constructing multiple decision trees.

## Evaluation Metrics
We use various metrics to evaluate the performance of the models, such as:
- **Accuracy**: Measures the overall correctness of the model.
- **Precision**: Measures the correctness of optimistic predictions.
- **Recall**: Measures how well the model captures actual positives.
- **F1 Score**: A weighted average of precision and recall.
- **Confusion Matrix**: Displays the true positives, false positives, true negatives, and false negatives.

## How to Run the Code
1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the notebook to train the model and evaluate the performance.

## Acknowledgment
This project is part of a college assignment, and the dataset is provided by the professor for academic purposes.
