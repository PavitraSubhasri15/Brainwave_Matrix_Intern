
# Credit Card Fraud Detection Using Machine Learning

## Overview
This project aims to detect fraudulent credit card transactions using machine learning. It applies data preprocessing, handles class imbalance, and trains a Random Forest model to classify transactions as fraudulent or legitimate.

## Dataset
The dataset used contains real-world credit card transactions. Since fraud cases are rare, we use SMOTETomek to balance the dataset by oversampling fraud cases and undersampling legitimate transactions.
[🔗 Dataset link used](https://www.kaggle.com/code/gauravduttakiit/creditcard-fraud-detection-by-logistic-regression/input)


## Project Steps
1. **Load Data** – Read the dataset and check for missing values.
2. **Data Preprocessing** – Handle missing values and split data into training and testing sets.
3. **Handling Imbalance** – Use SMOTETomek to balance the dataset.
4. **Model Training** – Train a Random Forest model with optimized parameters on half of the resampled data to reduce training time.
5. **Prediction & Evaluation** – Tune the classification threshold using Youden’s J statistic and evaluate using precision, recall, and ROC-AUC.
6. **Visualization** – Plot ROC curve for better understanding.

## Model Used
- **Random Forest Classifier**: Selected for its robustness and ability to handle imbalanced data effectively.
- **Optimized Parameters**: Limited tree depth and adjusted minimum sample splits to avoid overfitting.

## Results
- The model is evaluated using precision, recall, and ROC-AUC scores.
- A threshold tuning approach improves fraud detection without increasing false positives significantly.

## Conclusion
This project successfully demonstrates how machine learning can be used for fraud detection. Future improvements could include testing other algorithms like Gradient Boosting or deep learning for better accuracy.


