# 😀😟Sentiment Analysis😱😤
## Objective
The goal of this repository is to provide a tutorial for people who would like to extract sentiments from textual data. We include two reseach cases to illustrate two major sentiment analysis approaches: lexicon-based and machine learning.

## Introduction
There are various methods to investigate sentiments. This repository include a notebook about lexical methods (Vader and SentiWordNet). We apply the two methods to understand the sentiment expressed by visitors to Manuel Antonio National Park, Costa Rica. The lexicon-based methods deal with TripAdvisor reviews.


[Vader and SentiWordnet](https://github.com/luyuwang1993/Sentiment-Analysis/blob/dev-sentiment/Vader-and-SentiWordnet.ipynb "Vader and SentiWordnet")

[TripAdvisor Reviews Sample](https://github.com/luyuwang1993/Sentiment-Analysis/blob/dev-sentiment/review-info-sample.dat "TripAdvisor Reviews Sample")

Ther is the other notebook about supervised Machine Learning methods: Naive Bayes and Support Vector Machine (SVM). We adopt them to work with prelabeled tweets about airlines. Supervise approaches requires pre-classified data in order to train a classifier. You will find more details in the book chapters.


[Machine Learning with Naive Baues and SVM](https://github.com/luyuwang1993/Sentiment-Analysis/blob/dev-sentiment/Model-Train.ipynb "Model-Train.ipynb")

[Airline Tweets](https://github.com/luyuwang1993/Sentiment-Analysis/blob/dev-sentiment/Airline-Sentiment-Sample.csv "Airline Tweets")

## Requirements
You need the following libraries :
- pandas
- sklearn
- nltk
- numpy
- matplotlib

## Processing pipeline
The processing pipeline for two dataset is the following :

### Lexicon-based methods
- TripAdvisor reviews preprocessing: tokenization; stopword removal; spelling and grammar correction; resolving negations; lemmatizing or stemming...
- part-of-speech (POS) tagging: Retain adjectives and nouns
- Vader and SentiWordnet: Assign scores for reviews
- Classify the reviews
- Compare the performance of two algorithms

### Machine Learning Methods
- Tweets preprocessing: removal of Twitter-specific characters ( mentions: @, hashtags: #)
- POS tagging: assign every word to its POS tag (Retain adjectives and nouns)
- Training models based on Naive Bayes and Support Vector Machine (SVM)
- Draw diagrams based on five measurements: accuracy, balanced accuracy, precision, recall, and F1 scores.
- Evaluate model performance and select the number of features to report model performances
