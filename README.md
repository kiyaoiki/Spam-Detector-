# SMS Spam Classifier

A Python-based SMS spam detection project using Machine Learning techniques like **Naive Bayes** and **Logistic Regression**.



## Overview

This project classifies SMS messages as **spam** or **ham (not spam)** using Python and popular ML libraries. It includes data preprocessing, feature extraction using TF-IDF, model training, evaluation, and prediction on new messages.

**Key Features:**

- Cleans SMS messages: removes numbers, punctuation, and stopwords.
- Applies **Porter Stemming** for text normalization.
- Converts text into numerical features using **TF-IDF Vectorization**.
- Trains **Naive Bayes** and **Logistic Regression** models.
- Evaluates models using **accuracy, confusion matrix, and classification report**.
- Predicts new messages with a simple function.
- Saves the trained model and vectorizer for future use.



## Dataset

Uses the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) from the UCI Machine Learning Repository.



## Installation

1. Clone the repository:

```bash
git clone https://github.com/kiyaoiki/Spam-Detector-
