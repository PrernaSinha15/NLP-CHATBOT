# Combined 1
* The goal of this project is to create a chatbot that uses web-scraped data from Amazon India to close the gap between the amount of product information and
* the demand for individualised recommendations. Price, brand, memory, and rating are the four main product factors that are most important in influencing decisions to buy.
* The chatbot aims to improve customer happiness by streamlining the purchasing experience by allowing consumers to filter recommendations based on these parameters.
* Project involves comprehensive data preprocessing, exploratory data analysis, and feature engineering to enhance the accuracy of the predictive model.

# Preparation of dataset
* I've web scrapped the data from the amazon website and then I've done all the EDA processes on it.

# NLP
* for smoothly functioning of NLP I've used these libraries-
  *from sklearn.feature_extraction.text import TfidfVectorizer
  *from sklearn.metrics.pairwise import linear_kernel
  *import re
  *from nltk.tokenize import word_tokenize
  *from nltk.corpus import stopwords
  *from nltk.stem import WordNetLemmatizer

# Chatbot
* for creating a proper chatbot these library functions were used:
  *import random
  *import rew
  *import nltk
  *from nltk.chat.util import Chat, reflections
file
