# Assignment 14: Ethical AI Analysis and Explainability

## Project Overview

This project explores the importance of fairness and explainability in Artificial Intelligence. I used the Adult Income dataset to build a Logistic Regression model that predicts whether a person's income is above $50K.

The project also looks at whether the model performs differently between male and female groups and uses explainability tools to better understand how the model makes its predictions.

## What I Did

- Loaded and prepared the Adult Income dataset
- Selected numerical features for the model
- Used sex as the sensitive attribute for fairness analysis
- Split the data into training and testing sets
- Trained a Logistic Regression model
- Evaluated the model using accuracy, confusion matrix, and classification report
- Used Fairlearn to compare fairness metrics between groups
- Visualized selection rate, false positive rate, and true positive rate
- Used SHAP for global and individual model explanations
- Used LIME to explain an individual prediction
- Discussed ethical concerns and possible ways to improve fairness

## Results

The Logistic Regression model achieved **81.93% accuracy**.

The fairness analysis showed differences between the male and female groups. The selection rate was approximately **7.67% for females** and **15.13% for males**. These differences do not automatically prove that the model is unfair, but they show why fairness analysis is important.

SHAP showed that **capital-gain** had the strongest overall influence on the model. LIME also helped explain how different features influenced an individual prediction.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Fairlearn
- SHAP
- LIME
- Matplotlib

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. The Adult Income dataset will load automatically.
4. Install Fairlearn and LIME when prompted by the notebook.
5. Run the remaining cells to view the model evaluation, fairness analysis, SHAP explanations, and LIME explanation.

## Author

Mohammad Tamim Hamkar
