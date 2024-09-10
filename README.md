# Keyword Extraction Project

## Title
Keyword Extraction from Text Data

## Problem Statement
The goal of this project is to extract meaningful keywords from a given text. This helps in summarizing the content and identifying the main topics discussed.

## Results Interpretation
The results show the most relevant keywords extracted from the text using different methods. These keywords can be used for various applications like text summarization, topic modeling, and information retrieval.

## Methodology
We used three different methods to extract keywords from the text
1. KeyBERT
2. Traditional Method using NLTK
3. TF-IDF

## Steps Done
1. KeyBERT
   - Installed the KeyBERT library
   - Used KeyBERT to extract keywords from the text
2. Traditional Method using NLTK
   - Tokenized the text
   - Removed stop words
   - Counted word frequencies
   - Extracted the most frequent words as keywords
3. TF-IDF
   - Used TfidfVectorizer from sklearn
   - Fitted the vectorizer to the text
   - Extracted the top keywords based on TF-IDF scores

## Dataset
The dataset consists of a sample text about supervised learning. The text explains the concept of supervised learning, its methodology, and its applications. The text is used as input for all three keyword extraction methods to compare their performance.

