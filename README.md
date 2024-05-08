# Sentiment-and-Predictive-Analyses
The aim of this project is in twofold. First, it aims to get comfortable with Web Scraping social media data (Reddit, to be precise), run sentiment analysis of the data, and do some visualizations with it. Second, it aims to practice predictive analytics using the sentiment result of web-scrapped text data.

Therefore, the tasks are in two parts. 

First, identify a social issue (e.g, student loan forgiveness) and find a reddit post about it. The post should have at least 1000 comments. You are expected to scrape the comments (include the date created and the number of ups and downs the comments have attracted), pre-process the data, run a sentiment analysis (using both text blob and VADER), and conduct exploratory data analysis. In addition to this, create two columns - the first to consist of the number of characters in each comment, and the other to include the number of words in each comment. 

Second, you will build a Machine Learning model to predict the chances that a comment has a positive or negative sentiment. To do this, filter only the comments with positive and negative sentiments. Use the sentiment variable (with two categories - positive sentiment and negative sentiment) as your target variable, and use at least any three of number of ups, downs, character, words, as your features. As expected, you are to check for your model’s accuracy by presenting the necessary evaluation metrics (e.g, accuracy, precision, etc).
