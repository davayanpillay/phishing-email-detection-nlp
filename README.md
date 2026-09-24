# Phishing Email Detection Using NLP

## Overview

This project develops a machine learning classifier to distinguish phishing and spam emails from legitimate email messages using Natural Language Processing.

Multiple public email datasets were combined to create a large modelling dataset containing approximately 165,000 email records.

The project focuses on text preprocessing, TF-IDF feature extraction and supervised classification using Linear Support Vector Classification.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing
- TF-IDF
- LinearSVC
- Matplotlib
- Jupyter Notebook

## Methodology

The project workflow included:

1. Combining multiple email datasets
2. Data cleaning and preprocessing
3. Text normalisation
4. Train-test splitting
5. TF-IDF feature extraction
6. LinearSVC model training
7. Model evaluation
8. 5-fold cross-validation
9. Error analysis and model interpretation

## Key Results

- Test Accuracy: **96.21%**
- 5-Fold Cross-Validation Accuracy: **96.26%**
- Strong precision, recall and F1-score performance
- High ROC-AUC performance
- Low number of false positives and false negatives

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve / AUC
- 5-fold Cross-Validation

The results indicate that the classifier generalised effectively to unseen email data.

## Interpretability

TF-IDF feature weights were examined to identify terms associated with phishing/spam and legitimate email.

Examples of phishing or spam indicators included:

- click
- account
- urgent
- free
- winner

Examples of legitimate email indicators included:

- meeting
- report
- team
- project

## Limitations

The model may perform differently on completely new phishing campaigns, adversarial email content or language patterns that differ substantially from the training data.

Periodic retraining with newer phishing patterns would therefore be required for real-world deployment.

## Repository Contents

- `phishing_email_detection.ipynb` — complete modelling workflow
- `phishing_email_detection_report.pdf` — project methodology, evaluation and findings

## Author

Davayan Pillay  
BSc Information Technology (Data Science)  
Postgraduate Diploma in Data Analytics
