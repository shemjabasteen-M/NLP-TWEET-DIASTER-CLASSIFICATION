# NLP-TWEET-DIASTER-CLASSIFICATION

NLP-with-Disaster-Tweets-Kaggle
Natural Language Processing with Disaster Tweets ​. Predict which Tweets are about real disasters and which ones are not. What should I expect the data format to be?¶ Each sample in the train and test set has the following information:

The text of a tweet

A keyword from that tweet (although this may be blank!) The location the tweet was sent from (may also be blank) ## What am I predicting? You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0. ### Columns

id - a unique identifier for each tweet

text - the text of the tweet location - the location the tweet was sent from (may be blank) keyword - a particular keyword from the tweet (may be blank) target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

Import the libraries
Read the train and test datasets
Basic analysis on train and test datasets:
Cleaning the train and test datasets:
Exploratory Data Analysis
Text Preprocessing:
Train Test Split
Vertorization - TF-IDF on Train dataset
Model Building on Train data:
Prediction on Test Dataset:
Submission file:
