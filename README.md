Bitcoin & Crypto News Text Analysis

This project analyzes Bitcoin/Crypto-related news headlines using Python.
It performs data cleaning, sentiment analysis, topic modeling, and text visualization to extract insights from the dataset.

Project Overview

The goal of this project is to identify key topics, sentiment trends, and frequent word patterns in cryptocurrency-related news.
The process includes:

Cleaning and preprocessing text

Analyzing sentiment (Positive, Negative, Neutral)

Extracting topics using Non-Negative Matrix Factorization (NMF)

Finding frequent bigrams and trigrams

Creating visualizations like pie charts, bar charts, and word clouds

Features

Removes missing values, special characters, and stopwords

Tokenizes text and converts it to lowercase

Calculates sentiment scores and categories using TextBlob

Uses TF-IDF vectorization and NMF to find top 5 topics

Displays most frequent bigrams and trigrams

Saves intermediate and final results to Excel files

Requirements

Python 3
Libraries: pandas, nltk, textblob, scikit-learn, matplotlib, wordcloud

How to Run

Place your input Excel file as bitcoin.xlsx in the project folder.

Run the Python script to process the data and generate results.

The cleaned and analyzed files will be saved as:

bitcoin1.xlsx (cleaned data)

bitcoin2.xlsx (data with sentiment and topics)

Outputs

Sentiment distribution pie chart

Bar charts of top words for each topic

Word clouds for topic keywords

Bigram and trigram frequency lists

Future Improvements

Add live data collection from crypto news APIs

Build an interactive dashboard using Streamlit or Dash

Explore advanced topic modeling techniques like LDA or BERTopic

License

This project is licensed under the MIT License
