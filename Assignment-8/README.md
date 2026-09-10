# Assignment 8: Supervised Learning Classification

## Project Overview

This assignment uses the Breast Cancer Wisconsin dataset to build and compare supervised machine learning classification models. The goal is to classify breast cancer cases as malignant or benign and evaluate which model performs better.

## Dataset

The Breast Cancer Wisconsin dataset from Scikit-learn was used.

- 569 records
- 30 input features
- Target classes:
  - 0 = Malignant
  - 1 = Benign
- No missing values
- No duplicate rows

## Models Used

Two classification models were trained and compared:

1. Logistic Regression
2. Random Forest

## Model Results

### Logistic Regression
- Accuracy: 98.25%
- Precision: 98.61%
- Recall: 98.61%
- F1-score: 98.61%
- ROC-AUC: 0.995

### Random Forest
- Accuracy: 95.61%
- Precision: 95.89%
- Recall: 97.22%
- F1-score: 96.55%
- ROC-AUC: 0.994

Logistic Regression performed slightly better overall and was selected as the best model.

## How to Run

1. Open the notebook in Google Colab.
2. Run each cell from top to bottom.
3. The required libraries include pandas, numpy, matplotlib, seaborn, and scikit-learn.
4. The dataset is loaded directly from Scikit-learn, so no separate dataset download is required.

## Conclusion

This project helped me understand how supervised classification models can be prepared, trained, evaluated, compared, and considered for deployment and monitoring.
