# Spam Email Classifier (Python)  
A **machine learning–based system** that classifies emails as **Spam** or **Not Spam** using **Logistic Regression**.   The program extracts key features from email text (keywords, links, and capitalized words) and includes a **statistical anomaly detection check** to identify unusual sender behavior.

The dataset used in this project is **synthetic**.

## Features

### Machine Learning Classification
- Logistic Regression model for spam detection
- Balanced class handling
- Spam probability prediction

### Feature Extraction
- Suspicious keywords detection
- Link counting
- Capitalized word analysis

### Anomaly Detection
- Uses statistical analysis (CLT-based check)
- Flags unusual sender behavior patterns


**Project Files**

* spam_classifier.py — Main script
* email_dataset.xlsx — Synthetic dataset


## Requirements

Install the required Python libraries:

- numpy  
- pandas  
- scikit-learn  
- openpyxl  


**Usage**

1. Ensure email_dataset.xlsx is in the same folder as spam_classifier.py.
2. Run the script.
3. Enter the email content when prompted.
   

## Output

The script provides:

- Extracted feature counts
- Spam probability score
- Anomaly detection result
- Final verdict:
  - Spam  
  - Not Spam  
  - Suspicious (unusual sender behavior)


## Purpose

This project demonstrates:

- Machine learning classification workflow
- Feature extraction from text data
- Logistic Regression implementation
- Statistical anomaly detection
- Email security concepts
