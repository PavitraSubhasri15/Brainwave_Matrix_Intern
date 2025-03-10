#Fake News Detection Using Machine Learning

##Abstract

Fake news spreads misinformation and manipulates public opinion, making automated detection crucial. This project builds a machine learning model using Logistic Regression and TF-IDF vectorization to classify news articles as fake or real. The dataset consists of labeled real and fake news articles. The model is trained on preprocessed text data and optimized using GridSearchCV. Performance is evaluated based on accuracy and classification reports.

##Overview

This project applies Natural Language Processing (NLP) techniques to detect fake news. The data is preprocessed by removing noise, stopwords, and applying lemmatization. The text is then transformed using TF-IDF vectorization before being classified using Logistic Regression. The model is trained and tested on a balanced dataset, ensuring robust evaluation. Additionally, the trained model is saved and used for manual testing.

##Dataset

The dataset consists of two CSV files: Fake.csv (fake news articles) and True.csv (real news articles). Each file contains news articles labeled accordingly. A subset of the data is reserved for manual testing. The dataset is shuffled and split into training (75%) and testing (25%) sets. The text data is preprocessed to remove unnecessary symbols, links, and punctuation.

[🔗 Dataset link used ](https://www.kaggle.com/datasets/jainpooja/fake-news-detection)

##Project Goals

Build a reliable fake news detection model using Logistic Regression.

Preprocess text data using NLP techniques to improve accuracy.

Optimize model performance using GridSearchCV for hyperparameter tuning.

Evaluate performance based on accuracy, precision, recall, and F1-score.

Save the trained model for future predictions and manual testing.

##Algorithm

Data Preprocessing – Cleaning text by removing punctuation, stopwords, and lemmatizing words.

Feature Extraction – Applying TF-IDF vectorization to convert text into numerical features.

Model Training – Training Logistic Regression with hyperparameter tuning.

Prediction & Evaluation – Evaluating model performance using classification metrics.

Saving & Loading Model – Storing the trained model with joblib for future predictions.

##Conclusion

The Logistic Regression model with TF-IDF effectively classifies fake and real news. The model achieves high accuracy, demonstrating its ability to generalize well. Manual testing on unseen data further validates its reliability. Future improvements could include using deep learning models like BERT for better performance. This project provides a strong foundation for combating fake news using NLP and machine learning.

