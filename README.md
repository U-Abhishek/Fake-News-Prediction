# Fake-News-Prediction

## Introduction

The World Wide Web contains data in diverse formats such as documents, videos, and audio. Detecting and classifying news published online, especially in an unstructured format, is challenging and traditionally requires human expertise. However, computational techniques such as natural language processing (NLP) can detect anomalies and differentiate deceptive articles from factual ones.

## Features

This repository contains:
1. Implementation of a fake news prediction model.
2. Data gathered from various news articles and sources.
3. Front-end implementation using GRadio.

## NLP Model

The project utilizes the `TfidfVectorizer` model. 

- **Bag of Words (BoW)**: Converts text into a feature vector by counting the occurrences of words in a document, without considering their importance.
- **Term Frequency-Inverse Document Frequency (TFIDF)**: An enhancement of the BoW model, providing insights into the relevance of words in a document. TFIDF helps in information retrieval by identifying the importance of words, thereby improving the relevance of search results.

Example: Search engines use TFIDF values to provide the most relevant documents for a search query.

## Implementation

- **TfidfVectorizer_MODEL.ipynb**: Contains all the implementation details of the fake news prediction model.

## Data Sources

The data used in this project is sourced from:
1. [Google Drive Dataset](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)
2. [Kaggle Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
