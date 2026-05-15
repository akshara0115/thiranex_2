# thiranex_2
# Predictive Modeling with Machine Learning
This project demonstrates the implementation of a supervised learning pipeline to predict outcomes based on structured data. It covers everything from data preprocessing and model training to performance visualization using Random Forest and ROC Analysis.
# Overview
The primary goal of this project is to build a robust classification model. We use the Breast Cancer Wisconsin (Diagnostic) Dataset to classify tumors as either Malignant or Benign based on several clinical features.

# Tech Stack
Libraries:
scikit-learn: Model building and evaluation
pandas: Data manipulation
matplotlib & seaborn: Data visualization
# Project Workflow
Data Loading: Importing the dataset directly via sklearn.datasets.
Preprocessing: Splitting the data into training (80%) and testing (20%) sets to ensure unbiased evaluation.
Model Selection: Utilizing RandomForestClassifier for its ability to handle complex feature interactions.
# Evaluation:
Confusion Matrix: To visualize true vs. false predictions.
ROC Curve & AUC: To measure the model's ability to distinguish between classes.
Classification Report: Precision, Recall, and F1-Score analysis.
# Model Performance
The model consistently achieves high accuracy (typically >95% depending on the random seed). Below are the key evaluation visualizations produced by the script:
Confusion Matrix: Helps identify if the model is misclassifying malignant cases as benign.
ROC Curve: Displays the trade-off between the True Positive Rate and False Positive Rate.
