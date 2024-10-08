﻿# Ai_term_assignmernt
CSE3208
Task:
Your task is to build a simple machine learning model for a binary classification problem. You must
choose a dataset to help solve important healthcare problems. (datasets can be found online)
Build a Decision Tree and a K-Nearest Neighbors (KNN) classifier to predict the target variable based on
your selected dataset.

Steps:
Data Preprocessing:
• Load the dataset and examine its structure. (Hint: use head, shape, info, describe, etc. methods) •
The dataset should contain only numeric features. Remove the categorical features (if any) • Drop
the irrelevant features from the dataset. Also, handle the missing values appropriately • Split the
dataset into training and testing sets. Test set size will be set as –
the last 3 digits of your ID +5 (If your id is 0 to 9)

otherwise
the last 3 digits of your ID( % 10) + 5
Model Training:
• Initialize a decision tree and a KNN model using Scikit-learn
• Train both models on the training set
Model Evaluation:
• Evaluate the models on the testing set using appropriate metrics (e.g., accuracy, precision, recall,
F1-score)
• Mention which model performs better in terms of F1-score

Instructions:
• Include comments in your code to explain key steps
• Everyone should try to select different datasets
