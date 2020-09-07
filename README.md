# Twitter-Sentimental-Analysis

Python Script for sentimental analysis of tweets on ##Corona Virus##

First we will authenticate with twiter by using twitter developer credentials.Then we will grab the tweets on topic ##Corona## in furthur step we will clean and preprocess the data then we will find the polarity of each tweet.

Once you have this list of tweets , run a sentiment analysis on for each tweet and finally the output should be in the below format

* Tweet
* Polarity
* Subjectivity
* Sentiment ( Negative,Positive,Neutral )

#Requirements-
  [Python >= 3.6.1 (64-bit)](https://www.python.org/downloads/)
  [Tweepy](http://www.tweepy.org/) - OpenSource Twitter API for Python.
  [WordCloud](https://pypi.org/project/wordcloud/) - 
  [Textblob](https://textblob.readthedocs.io/en/dev/) - Python library using [nltk](https://www.nltk.org/) to find polarity of text/tweet.
  [API Keys for Twitter](https://developer.twitter.com/) 
  Pandas
  Matplotlib
#Dependencies-
  Install Tweepy pip install tweepy
  Install TextBlob pip install -U textblob
  pip install wordcloud
  Additional Dependency python -m textblob.download_corpora
More enhancements coming soon!
