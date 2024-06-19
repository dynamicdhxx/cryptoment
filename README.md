# Cryptoment - The Cryptocurrency Sentiment Analysis
# Cryptocurrency Sentiment Analysis

The aim of this project is to produce a Twitter Sentiment Analysis on the cryptocurrency market. With the rise in popularity of Bitcoin and Ethereum and the majority of  businesses moving to the web3.0 it is important to understand how the consumer actually feels about this change.
Cryptoment analyzes most recent and relevant tweets related to crypto trading with the help of cardiffnlp/twitter-roberta-base-sentiment-latest model which is a RoBERTa based NLP model from hugging face; and rates it a negative, neutral, or positive sentiment accordingly.
          
## Requirements

**To run this project, you will need to add the following Libraries to your system :-**
- transformers
- torch
- requests
- re
- pandas
- numpy 
- snscrape
- matplotlib
- seaborn

## Result 

![Histogram showing the `Sentiment Scores` plotted against `The Number of Tweets` ](https://github.com/dynamicdhxx/cryptoment/blob/main/Result.png)

Here, the `Sentiment Scores` have been plotted against `The Number Of Tweets`.

- X-axis:- Sentiment Scores
- Y-axis:- Number Of Tweets

In this project the negative tweet was assigned a sentiment score of  1. Similarly 2 was assigned to neutral and 3 to positive.

The histogram plotted showed that most of the tweets had a score of 3.









