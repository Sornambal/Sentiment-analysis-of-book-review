# Sentiment-analysis-of-book review using NLP

This project performs sentiment analysis on book reviews using a Naive Bayes classifier combined with TF-IDF vectorization. The goal is to classify the sentiment of a review as either positive or negative or neutral. The code includes preprocessing steps for text data, handles class imbalance through oversampling, and evaluates the model's performance using classification metrics.


Features

1.Text Preprocessing: Tokenization, stopword removal, and lemmatization using NLTK.
2.Class Imbalance Handling: Oversampling with imblearn's RandomOverSampler to address imbalanced classes.
3.TF-IDF Vectorization: Feature extraction using bigrams.
4.Naive Bayes Classifier: Predicts sentiment using the Multinomial Naive Bayes algorithm.
5.Model Evaluation: Includes classification report showing precision, recall, F1-score, and accuracy.
