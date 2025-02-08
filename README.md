# Fake news prediction

## Overview

This project is using the dataset from : "https://www.kaggle.com/competitions/fake-news/overview". The goal being to be able to predict if a certain article is fake or not.  
It uses python with pandas, re, nltk and sklearn on google collab.  

## What i learned

data.isnull().sum() : check null values in dataset. Here fill na with ''  
re.sub('[^a-zA-Z]', ' ', content) used ta replace from content everything that is not from a to z or A to Z   
nltk corpus stopwords : list of stopwords which words with no value for the model in multiple language  
nltk porter stemmer : used to replace a word with its elementary form : acting --> act  
stemmed_content.lower() : put everything lower case  
stemmed_content.split() : output list with every word split   
stemming function goal is to use PorterStemmer to go from whole text to only the important word of a text  
pd.DataFrame.apply(function) : apply a function to a particular column  
TfidfVectorizer : used to go from words to number for the model to understand  

## Credits

This project has been made by following this video : "https://www.youtube.com/watch?v=nacLBdyG6jE&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=8&ab_channel=Siddhardhan" from Siddhardhan channel.  

# Fake-News-Prediction
