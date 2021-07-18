# Twitter-Sentiment-Analysis

![joshua-hoehne-Lh_sFxD8AkI-unsplash](https://user-images.githubusercontent.com/77420780/126051543-c027459a-55af-4dc1-8582-bbd8717203ba.jpg)

# Background
Twitter is a platform where people express their feelings towards the current context. As humans, we can guess the sentiment of a sentence whether it is positive or negative.  


# Problem statement
There are numerous forms of social media out there, and there is so much information on the web. It is a case of too much information but too little time to take in the information. In this example, we are utilizing A.I to assist us in deciphering the information and general sentiment of a certain topic


# Technologies Used
* Tweepy
* textblob
* re(for regular expressions)


# Methodology
In this project I have used “Tweepy,” which is an easy-to-use Python library for accessing the Twitter API. A Twitter developer account and access codes to do this analysis. The API will call the real time tweets of the subject we wish to further understand. I have used object oriented programming to create a class for the Twitterclient and to segregate the various task(i.e cleansing , and getting sentiment score) into functions

Sentiment of tweets are analyzed as positive, negative and neutral. Tweepy is used to collect tweets which requires twitter development account. Tweets are cleaned as they contain RT,url @username etc. Also stopwords, punctuation are removed as part of data cleaning.

Once the data have been cleansed, i performed natural language processing and sentiment analysis to get the positive and negative score of a the tweets to know the general sentiment of a tweet.

# Sample of how output looks like:
The result will be a percent of the sentiment score. i.e (The percentage of positive sentiment on crypto is 38.15789473684211,
The percentage of negative sentiment crypto is 6.578947368421052)
