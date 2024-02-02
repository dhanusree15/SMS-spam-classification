# SMS Spam Classification Project

This repository contains code for a spam classification project using machine learning. The project focuses on classifying emails as spam or non-spam based on their content.

## Dataset

The dataset used in this project is from the file `spam.csv`. It includes information about email messages and their corresponding labels (spam or non-spam).

## Libraries Used

- pandas
- matplotlib
- seaborn
- scikit-learn

## Data Preprocessing

- Removed unnecessary columns (`Unnamed: 2`, `Unnamed: 3`, `Unnamed: 4`)
- Encoded the target variable `v1` using Label Encoding

## Tokenization and TF-IDF Vectorization

- Utilized TfidfVectorizer for tokenization and TF-IDF vectorization of the email content

## Train-Test Split

Split the data into training and testing sets using an 80-20 split ratio.

## Naive Bayes Model

- Implemented a Multinomial Naive Bayes classifier
- Achieved a high accuracy of 98.21% on the testing set

## Logistic Regression Model

- Utilized logistic regression for spam classification
- Achieved an accuracy of 95.52% on the testing set

## Support Vector Machine Model

- Implemented a Support Vector Machine classifier with probability estimates
- Achieved a high accuracy of 97.67% on the testing set

## Model Evaluation Metrics

For each model, the following metrics were calculated:

- Accuracy
- Confusion Matrix
- Classification Report

## ROC Curve

Plotted ROC curves to visualize the performance of the models in terms of true positive rate and false positive rate.

