# classification-challenge
Module 13 Challenge Matt Rodosky
Project Overview

This project demonstrates a supervised machine learning approach to build a spam detection classifier for an Internet Service Provider (ISP). The model aims to accurately classify emails as either "spam" or "not spam,"
Two classification models were built and evaluated:

    Logistic Regression
    Random Forest Classifier

Files

    spam_detector.ipynb: Jupyter notebook containing the full code for data loading, preprocessing, model training, and evaluation.
Data
    Data was provided by the UCI Machine Learning Library
Methodology

    Data Preparation:
        The dataset was loaded and split into features (X) and labels (y).
        A balance check on labels was conducted using value_counts() to assess any class imbalance.

    Data Splitting:
        The data was split into training and testing sets using train_test_split to ensure unbiased evaluation.

    Feature Scaling:
        Features were scaled using StandardScaler to ensure compatibility and improve performance of the models, especially logistic regression.

    Model Development:
        Logistic Regression and Random Forest Classifier models were created and trained on the scaled training data.
        The random_state parameter was set to 1 to ensure reproducibility.

    Evaluation:
        Each model’s performance was evaluated using the accuracy score on the testing data.
        The accuracy scores were compared to determine the better-performing model.

Results

    Which model performed better?
    Random Forest 
    How did the results compare to the initial prediction?
    Initial prediction thought that the logistic regression model would perform better.

    Some starter code for the project was provided by instructor in starter file. Primarily code that imported libraries and dependencies, imported and displayed the dataframe.