# Assignment 10: Customer Review Sentiment Analysis

## Overview
In this project, I analyzed Amazon Alexa customer reviews to classify them as positive or negative. I compared traditional machine-learning models with BERT to see which model performed best.

## Methods
- Data cleaning and preprocessing
- Bag of Words and TF-IDF
- Word2Vec with PCA
- Logistic Regression
- SVM
- GridSearchCV
- Fine-tuned BERT
- Model evaluation using Accuracy, Precision, Recall, F1 Score, and ROC-AUC

## Results

| Model | Accuracy | F1 Score | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 92.06% | 95.86% | 92.38% |
| SVM | 92.86% | 96.25% | 92.65% |
| BERT | 94.92% | 97.28% | 97.37% |

BERT gave the best overall performance, so I selected it as the final model.

## How to Run
1. Open the notebook in Google Colab.
2. Connect Google Drive and load the Amazon Alexa dataset.
3. Run the cells in order.
4. Review the model results and visualizations.

## Author
Mohammad Tamim Hamkar
