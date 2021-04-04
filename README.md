# AITA Analysis
Text analysis on posts from subreddit [/r/AmItheAsshole](https://www.reddit.com/r/AmItheAsshole/). 
## Project Objective
The purpose of this project is to see the difference between two groups (asshole group vs. non-asshole group) by analyzing texts from submitted posts.

## Methods Used
* Topic Modeling
* Natural Language Processing
* TF-IDF
* NMF
* LDA
* etc

## Technologies
* SpaCy
* Scikit-learn
* Python
* Praw
* NLTK
* etc

## Project Description
Analyzed text from subreddit posts collected using Praw and Google Big Query. Preprocessed text by removing stop words, entities, lemmatization using SpaCy. Vectorized processed text using scikit-learn TF-IDF vectorizer and applied NMF to get the topics brought up often on this subreddit group.
