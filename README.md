# Depression Detector

This code extracts data from a Twitter dataset, performs sentiment analysis on the tweets, and selects the best classifier based on accuracy. The extracted tweet texts are cleaned, tokenized, and transformed using TF-IDF scores. The code then splits the data into training and testing sets, trains and tests various classifiers, and selects the best performing one for deployment.

## Prerequisites
- Python 3.x
- Required libraries: zipfile, os, json, re, bs4, nltk, sklearn
- NLTK data: stopwords, word_tokenize
- Twitter dataset: dataset.zip

