# Phishing URL Detection using Machine Learning

## Introduction
Phishing attacks are a significant cybersecurity threat, involving fraudulent attempts to obtain sensitive information by masquerading as a trustworthy entity. This project applies machine learning techniques to detect phishing URLs, helping prevent potential cyber threats.

## Dataset
The dataset used is the [Phishing Dataset for Machine Learning](https://www.kaggle.com/datasets/shashwatwork/phishing-dataset-for-machine-learning) from Kaggle. It includes various features extracted from URLs and a binary target variable indicating whether a URL is legitimate (0) or phishing (1).

## Models and Results

### Decision Tree
- **Accuracy:** 95%
- **Cross-validation Mean Accuracy:** 95.43%
- **Precision, Recall, F1-score:** 95% (for both classes)
- **Confusion Matrix:** 
  - TP: 1971, TN: 1848, FP: 94, FN: 87

### Random Forest
- **Accuracy:** 98%
- **Cross-validation Mean Accuracy:** 98.09%
- **Precision, Recall, F1-score:** 98% (for both classes)
- **Confusion Matrix:** 
  - TP: 994, TN: 970, FP: 18, FN: 18

### Logistic Regression
- **Accuracy:** 94%
- **Cross-validation Mean Accuracy:** 94.65%
- **Precision:** 95% (phishing), 93% (legitimate)
- **Recall:** 93% (phishing), 95% (legitimate)
- **F1-score:** 94% (for both classes)
- **Confusion Matrix:** 
  - TP: 959, TN: 918, FP: 70, FN: 53

## Conclusion
- **Random Forest:** Best performance with 98% accuracy.
- **Decision Tree:** Consistent performance with 95% accuracy.
- **Logistic Regression:** Good performance with 94% accuracy.

## How to Run
1. Clone the repository.
2. Install the required libraries: `pip install -r requirements.txt`.
3. Run the Jupyter notebooks to train and evaluate models.

## Visualizations
- Feature Importances (Random Forest)
- Decision Tree Visualization
