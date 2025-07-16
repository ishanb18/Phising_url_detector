# Phishing URL Detector 🛡️

A machine learning-based project to detect phishing URLs using various features extracted from the URL structure and content.

## 📌 Author

**Ishan Bansal**

## 📖 Project Overview

This notebook implements a machine learning pipeline that:
- Loads a dataset of URLs labeled as phishing or legitimate.
- Extracts and engineers relevant features from URLs.
- Trains and evaluates several classification models.
- Predicts whether a new URL is likely to be a phishing attempt.

## 📁 Files

- `Phising_url_detector.ipynb`: Main Jupyter notebook for the project.
- `README.md`: This documentation file.

## ⚙️ Requirements

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

Main libraries used:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `urllib`
- `re`

## 🚀 Getting Started

 Run the notebook using Jupyter or VS Code.

## 🧪 Model Evaluation

The notebook evaluates different models including:
- Logistic Regression
- Random Forest
- XGBoost (if used)

Evaluation metrics include:
- Accuracy
- Confusion Matrix
- Classification Report

## 🛠️ Feature Extraction Techniques

- Domain length
- Use of `https`
- Presence of `@`, `//`, or IP addresses
- Number of subdomains

## 📊 Results

Model performance is displayed using:
- Confusion matrix
- ROC curves (if plotted)
- Accuracy scores

