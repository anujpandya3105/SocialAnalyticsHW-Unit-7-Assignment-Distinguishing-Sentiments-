# SocialAnalyticsHW-Unit-7-Assignment-Distinguishing-Sentiments-

# Overview/Synopsis
The assignment required to plot out the results of the sentiments posted on twitter fpr 5 major Media companies -
BBC, CBS, CNN, FOX and NY Times

# My Solution / Approach:
1. Create a tuple of the twitter handles for each of the media companies
2. Foreach media company perform a Vader analysis of every one of the most recent 100 tweets.
  The polarity scores for each media company is stored in a list of dictionaries. The dictionary comprises of a key/value
  pair of the results from the Vader analysis. The keys being - compound(plotted as Tweet Polarity), neutral, negative, positive, 
  tweet text and a counter(Tweets Ago). 
3. Tweet results for every company have been plotted. 
