# sentimentAnalysis
Sentiment analysis using TextBlob library in Python to find correlation between stock price and Twitter sentiment

This repository consists of IPYNB files using Python 3 to collect, process, and analyse Twitter sentiment about CIMB Niaga Indonesia.

# TweetVac
Python package to collect tweets in a specific range of time (https://pypi.org/project/tweetvac/).

# TextBlob
Python library for processing textual data. This project using Python 3 version (https://pypi.org/project/tweetvac/). Using Sentiment Analysis from TextBlob to compute tweets' polarity scores. Polarity score of the tweets will be used to categorize level for positive, neutral, or negative tweet.

# google-trans-new
Google Translate API for Python. The tweets will be translated to English, since the TextBlob Sentiment Analysis doesn't support Indonesian language. 

# Analysis
Tweet sentiment will be processed for correlation test using Kendall Tau correlation and accuracy test using cross validation and k-fold cross validation.
