# NLP disaster tweets

A simple NLP project to classify disaster tweets.
For this dataset, vectorzing text using N-gram Count Vectorizer including Unigrams and bi-grams, significantly improved model performance over Tfidf Vectorizer. And Xgboost classifier was able to outperform Random forest, giving better accuracy and F1-score

Techniques used :

Data cleaning:

Remove punctuations
Removing usernames
Removing links
Removing Stopwords
Lemmatizing words

Vectorizer:
N-gram Count Vectorizer including Unigrams and bi-grams
Excluding maximum and minimum frequency tokens from the final data.


Model:
Xgboost : XGBClassifier

Evaluation using:
Recall, Precision, Accuracy and F1-score

Competition link:
https://www.kaggle.com/c/nlp-getting-started/overview
