# Sentiment Analysis Project


This repository contains a Python project for sentiment analysis using natural language processing (NLP) techniques. The project utilizes various libraries, including pandas, nltk, wordcloud, matplotlib, and scikit-learn, to preprocess textual data, generate word clouds, and build machine learning models for sentiment classification.


## Project Structure
sentiment_analysis.ipynb: Jupyter Notebook containing the main project code.




# Code Overview


## Data Preprocessing


1. Loading the Dataset: Reads the Sentiment140 dataset into a pandas DataFrame.


2. Text Preprocessing Functions:


* remove_urls_mentions: Removes URLs and mentions from text.
* tokenize_text: Tokenizes the text into words.
* remove_stop_words: Removes stop words from the list of words.
* perform_lemmatization: Lemmatizes each word.
* remove_punctuations_numbers: Removes non-alphabetic words.
* emojis_encode: Encodes emojis in the text.
* replace_consecutive_letters: Replaces 3 or more consecutive letters with 2 letters.
* remove_short_words: Removes words with a length less than 2.

  
3. Data Preprocessing: Applies the preprocessing functions to clean and prepare the text data.




# Exploratory Data Analysis (EDA)


1. Word Clouds: Generates word clouds for positive and negative sentiments.
  

2. Sentiment Distribution Over Time: Visualizes the sentiment distribution over time using histograms and daily counts.




# Machine Learning Models


1. Train-Test Split: Splits the preprocessed data into training and testing sets.


2. TF-IDF Vectorization: Converts the text data into TF-IDF vectors.


3. Machine Learning Models:


* Naive Bayes
* Logistic Regression


4. Model Evaluation: Computes accuracy and classification reports for the trained models.
