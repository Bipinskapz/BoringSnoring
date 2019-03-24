# Sentiment Analysis

Sentiment analysis can be done in two ways:

1. Rule Based Sentiment Analysis
2. Machine Learning Based Sentiment Analysis


### Rule-Based Sentiment Analysis:

It uses a lexicon of sentiment related words to predict the sentiment of a sentence.

The lexicon has many sentiment related words with each word corresponding to a positive or negative value.When a sentence is given for sentiment analysis, the number of words with positive and negative points are counted. If the number of words with positive point is more than that of negative ones, then the polarity of sentiment is positive :) and vice versa :(

### Dependencies

1. **Tweepy** is the library used for accessing the twitter API which is required for collecting the tweets for sentiment analysis.
2. **Pandas** is used for dataset(tweets) manipulation.
3. **NLTK** is required for predicting the score of sentiment or polarity of sentiment based on vader lexicon.


You can get create a twitter API from [here](https://developer.twitter.com/apps).

 
