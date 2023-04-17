# MLAI_Module17

## Overview
This project is a Practical Assignment Module 17. Here I compare the performance of the classifiers namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. 

## Goal
I have utilize a dataset related to marketing bank products over the telephone. The goal of this project is to predict if a client will subscribe the deposit, not regarding which amount is retained, turning it a classification task. Specifically for the business, the goal is to increase efficiency of directed campaigns for long-term deposit subscriptions by reducing the number of contacts to do.

## Dataset and Notebook
The link to the dataset is: https://github.com/Apeksha-Sridhar/MLAI_Classification/blob/main/bank-additional-full.csv
The link to the Jupyter Notebook is: https://github.com/Apeksha-Sridhar/MLAI_Classification/blob/main/prompt_III.ipynb

## Data Findings
The most important bank information features that were selected are students, age, retired folks, illiterate, default_no, unemployed and married folks.
Using default parameters:
 a. the best accuracy models are Baseline, logistic regression and SVM models.
 b. the fastest models are Baseline and Decision Tree models.
After tuning for the best parameters:
 b. the best recall score models are Logistic Regression and SVM
Overall, for this task, the best model in my opinion is Logistic Regression, considering it also took the least amount of time.

## Business Findings
The features that are useful in predicting whether a customer will subscribe are not are whether the customer is a student, their age, whether they are retired, illiterate, don't have credit set to default, are unemployed and are married.

While most of the above customer characteristics positively predict the outcome, not having credit in default negatively predicts the outcome.

More accuracte predictions can be made once more data is collected.

## Next Steps and Recommendations
Models are not very good due to the imbalance of classes. So next step could be to:
 a. Collect more data
 b. Undersample majority class
 c. Oversample the minority class
Try training the models with not just the bank information features but all the other features as well.
Stratify the data during the train_test_split due to the imbalanced classes, which will possibly provide better precision scores.
