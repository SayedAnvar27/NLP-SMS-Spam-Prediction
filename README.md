Introduction:

This project demonstrates how to build a simple yet effective spam detection model using the CountVectorizer 
for text preprocessing and a Naive Bayes classifier.

Dataset:

The dataset used in this project consists of SMS messages labeled as spam or not spam (ham)

Features:

CountVectorizer: Converts SMS text into a matrix of token counts.
Naive Bayes Classifier: Trains a Multinomial Naive Bayes classifier on the vectorized text data.

Model Training:

The model training process involves:
Loading the SMS dataset.
Preprocessing text data using CountVectorizer to convert text into numerical features.
Splitting the dataset into training and testing sets.
Training a Naive Bayes classifier on the training data.
After check its accuracy of detection and score
