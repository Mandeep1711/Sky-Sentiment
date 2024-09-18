# Sky-Sentiment
**Project Overview**
This project focuses on analyzing a dataset that contains airline-related tweets, sentiment scores, and other relevant details. The primary goal is to conduct sentiment analysis on the dataset and assess the accuracy of the sentiment predictions.

**Dataset Description**
The dataset includes multiple features, such as:

- tweet_id: A unique identifier for each tweet.
- airline_sentiment: The sentiment associated with the tweet (positive, negative, or neutral).
- airline_sentiment_confidence: The confidence level of the sentiment classification.
- negativereason: The reason behind any negative sentiment.
- negativereason_confidence: The confidence score for the reason given for negative sentiment.
- airline: The airline referenced in the tweet.
- airline_sentiment_gold: The "gold" label for sentiment, available for a subset of tweets.
- name: The username of the person who posted the tweet.
- negativereason_gold: The "gold" label for negative sentiment reasons for certain tweets.
- retweet_count: The number of times the tweet was retweeted.
- text: The content of the tweet itself.
- tweet_coord: The geographical coordinates where the tweet was posted.
- tweet_created: The timestamp when the tweet was posted.
- tweet_location: The user's location when they posted the tweet.
- user_timezone: The user's timezone at the time of the tweet.

**Key Phases**
Data Exploration: The dataset is thoroughly examined to understand its structure and key characteristics.

Data Cleaning & Preprocessing: The dataset is preprocessed, including addressing missing values and preparing text data for analysis.

Sentiment Analysis: Text data is analyzed to categorize tweets as either positive, negative, or neutral.

Model Evaluation: The accuracy of the sentiment classification is calculated to gauge the model's performance.

**Final Insights**
This project involves sentiment analysis of tweets related to airlines, aimed at identifying customer sentiment trends. By analyzing the sentiment, airlines can gain a better understanding of customer opinions and areas for improvement. The sentiment analysis model used in this project achieved an accuracy rate of approximately 73.06%, offering useful insights into customer feedback that can help airlines enhance service quality and customer satisfaction.
