# Sentiment Analysis with IMDb Movie Reviews
 
This project performs sentiment analysis on IMDb movie reviews using Python and the Natural Language Toolkit (NLTK) library. The goal is to classify movie reviews as positive or negative based on their text content.

## Overview
+ Dataset: IMDb movie reviews dataset from NLTK.
+ Approach: Naive Bayes classifier for sentiment analysis.
+ Metrics: Confusion Matrix.

## Pip Install
```
pip install nltk scikit-learn
```

## Steps
1. Dataset Preparation: IMDb movie reviews dataset is loaded and preprocessed.
2. Feature Extraction: Text data is tokenized, stop words are removed, and words are lemmatized.
3. Model Training: Naive Bayes classifier is trained on the vectorized text data.
4. Model Evaluation: Classifier performance is evaluated using accuracy and confusion matrix.
5. Results Visualization: Confusion matrix is plotted to visualize the model's performance.

## Resources
[NLTK Documentation](https://www.nltk.org/)

[scikit-learn Documentation](https://devdocs.io/scikit_learn/)
