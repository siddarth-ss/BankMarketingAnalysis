# BankMarketingAnalysis
# Abstract
This repository contains the analysis of the Bank Marketing Dataset with the goal of predicting customer subscription to a bank term deposit. The classification problem was addressed by identifying influential factors and applying various machine learning models.

# Introduction
The dataset involves direct marketing campaigns of a Portuguese banking institution, focusing on phone calls. The analysis aims to recognize attributes influencing customers' decisions to subscribe to a bank term deposit.

# Data Description
UCI Machine Learning Repository: Bank Marketing Data Set
21 attributes, 41,188 records
Categorical and Numerical Variables
# Exploratory Data Analysis
Data exploration and visual representation
No null values detected
Graphical representations for key insights
Data Pre-processing
Correlation plot for feature selection
Data reduction using Principal Component Analysis (PCA)
Feature engineering: Dummy variables for categorical variables
Handling imbalanced data with SMOTE
Methods
Logistic Regression

Tolerance: 0.65, Learning Rate: 0.00001, Max Iterations: 400
Training Accuracy: 81.93%, Test Accuracy: 80.81%
Naive Bayes

Gaussian Naïve Bayes algorithm
Non-parametric model
Hard Margin SVM

Learning Rate: 0.00001, Lambda: 0.001, Iterations: 200
Training Error: 11.51%, Test Error: 15.56%
KNN

k=3
Best Test Accuracy: 85.38%
# Results
Model	Accuracy	Error	Recall	Precision	F1 Score
Logistic Regression	80.0%	18.9%	95%	36%	53.04%
Naive Bayes	81.61%	18.39%	43.2%	28.8%	34.56%
Hard Margin SVM	84.44%	15.56%	91.58%	41.33%	56.95%
KNN	85.38%	14.62%	65.15%	40.64%	50.06%
# Discussion
KNN performed best with 85.38% accuracy, followed by SVM with 84.44%. However, considering computational efficiency, Hard Margin SVM produced quick results within approximately 3 mins, making it a practical choice.
