# Sentiment-Analysis-with-Python-NLTK-Text-Classification
~ Machine Learning Project

~ Segregating given dataset of IMDB reviews into good and bad reviews using sentiment analysis.

## Introduction ##

Given the availability of a large volume of online review data (IMDB, etc.), sentiment analysis becomes increasingly important. In this project, a sentiment classifier is built which evaluates the sentiment of a piece of text being either positive or negative. 

## Getting the Dataset ##

The "IMDB Dataset" shall be used for this project. The dataset is compiled from a collection of 25,000 reviews from IMDB on the condition there are no more than 30 reviews per movie. Neutral reviews are not included. The 25,000 reviews are divided evenly into the training and test set. 

## Data Preprocessing ##

The csv file has three columns,"id",“review” and “sentiment”. The column “review” contains review texts and the column “sentiment” consists of sentiment labels, 1 for positive and 0 for negative. In addition, common English stopwords should be removed. An English stopwords reference ('stopwords.en') is given in the code for reference.


## Algorithmic Overview ##




## Functions used in the copy1.ipynb file##

review_to_words : Function to convert a raw review to a string of words
                  # The input is a single string (a raw movie review), and 
                  # the output is a single string (a preprocessed movie review)
                  # It remove Html tags
                  # In Python, searching a set is much faster than searching a list, so converts the stop words to a set
                  # Removes stop words
## Environment ##

Language : Python

Libraries : Scikit, Pandas, bs4, nltk

## Result ##
Here, 1 is given for positive labels and 0 is for negative labels 
