# NLP Pipeline on IMDB Movie Reviews

## Overview
An end-to-end NLP pipeline applied on 2000 IMDB movie reviews.

## Pipeline Steps
- Text Preprocessing (HTML removal, punctuation, stopwords, lemmatization)
- Bigram Analysis (positive vs negative reviews)
- Named Entity Recognition (most mentioned persons)
- Sentiment Classification (Logistic Regression, Naive Bayes, Linear SVM)

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 81.5% |
| Naive Bayes | 83.0% |
| Linear SVM | 83.6% |

## Dataset
IMDB 50K Movie Reviews — [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Libraries Used
NLTK, spaCy, scikit-learn, pandas, matplotlib
