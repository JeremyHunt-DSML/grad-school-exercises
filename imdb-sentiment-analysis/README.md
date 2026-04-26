# IMDb Movie Review Sentiment Analysis

## Overview
This exercise focuses on applied Natural Language Processing (NLP) and predictive modeling to classify IMDb movie reviews as either positive or negative sentiment. It demonstrates the end-to-end process of cleaning text data, extracting features, and evaluating multiple machine learning algorithms.

## Key Skills & Technologies Demonstrated
* **Python Libraries:** `pandas`, `scikit-learn`, `nltk`
* **Text Preprocessing:** Vectorizing cleaned text data.
* **Feature Engineering:** TF-IDF Vectorization (with strict train/test boundaries to prevent data leakage).
* **Classification Models Trained:** * Logistic Regression
  * Naive Bayes
  * LinearSVC
  * Random Forest
* **Model Evaluation:** Accuracy, Precision, Recall, F1-Score, Confusion Matrices, and ROC curves.

## Key Takeaways
By strictly fitting the vectorizer on the training data to avoid data leakage, the evaluation metrics reflect how these models handle genuinely unseen data. Even with a baseline TF-IDF setup, the models successfully classified sentiment, establishing a strong foundation for future optimization using n-grams or neural word embeddings.
