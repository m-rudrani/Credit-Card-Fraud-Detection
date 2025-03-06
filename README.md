# Credit Card Fraud Detection

## Project Overview
This project implements **Credit Card Fraud Detection** using **XGBoost**, a powerful gradient boosting algorithm. The dataset is highly imbalanced, so techniques like **SMOTE oversampling** and **PCA for dimensionality reduction** are used to improve performance.

## Dataset
The dataset consists of anonymized credit card transactions labeled as:
- **0** → Legitimate transactions
- **1** → Fraudulent transactions

### Class Imbalance
Fraudulent transactions make up **only 0.1727%** of the dataset, requiring techniques like **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the classes.

## Installation & Setup
To run this project, install the necessary dependencies:
```bash
pip install -r requirements.txt
```

## Features Implemented
**Data Preprocessing** (Handling missing values, feature scaling)
**PCA for Dimensionality Reduction**
**SMOTE for Oversampling**
**XGBoost Model Training & Evaluation**
**SHAP for Model Explainability**


## Clone the Repository
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

## Model Performance Metrics
After training, the model is evaluated using:
- **Accuracy**
- **Precision & Recall**
- **Confusion Matrix**
- **F1-score**
- **SHAP Feature Importance Analysis**

## Contributing
Feel free to submit **issues** and **pull requests** if you want to improve this project!

## License
This project is **open-source** and available under the [MIT License](LICENSE)
