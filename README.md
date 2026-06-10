
# Spam Email Prediction System

A machine learning model that classifies emails as spam or not spam using NLP techniques.

## Tech Stack
Python · scikit-learn · pandas · NumPy · TF-IDF Vectorization

## How It Works
1. Raw email text is cleaned and preprocessed
2. TF-IDF vectorization converts text to numerical features
3. A classification model (Logistic Regression / Naive Bayes) predicts spam vs. ham

## Results
- Dataset: UCI SMS Spam Collection (mail_data.csv)
- Accuracy: 96.7%

## Run Locally
pip install scikit-learn pandas numpy
jupyter notebook spam_email_classifier.ipynb
