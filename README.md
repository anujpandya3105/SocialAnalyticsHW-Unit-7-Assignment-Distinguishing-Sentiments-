# SocialAnalyticsHW-Unit-7-Assignment-Distinguishing-Sentiments-

# Overview/Synopsis
The assignment required to plot out the results of the sentiments posted on twitter for 5 major Media companies -
BBC, CBS, CNN, FOX and NY Times

# My Solution / Approach:
1. Create a tuple of the twitter handles for each of the media companies
2. Foreach media company perform a Vader analysis of the recent 100 tweets.
  The polarity scores for each media company is stored in a list of dictionaries. The dictionary comprises of a key/value
  pair of the results from the Vader analysis. The keys being - compound(plotted as Tweet Polarity), neutral, negative, positive, 
  tweet text and a counter(Tweets Ago). 
3. Tweet results for every company have been plotted. This is achieved by storing the results of the vader analysis for each company
  in a list and plotting it. Then initialize the list after the loop of the company being processed 
  to store information about the next company, till the loop of companies is exhausted.
4. Next step is to draw a scatter for all the companies in one scatter plot. This is done by storing results of the Vader analysis, 
  in a list as in step 3 above, EXCEPT that this list is NOT reset after every iteration of a company. Convert this to a dataframe.
5. From the Data Frame created above , create 5 smaller data frames for each media company. This is done to render uniqueness to 
  each comapny by allocating a unique color.
6. Plot a scatter for each dataframe and add a legend to show what color represents a company.
7. Use the data to plot a Bar Chart as well.

# Execution of program and outputs
The program can be executed using Jupyter notebook by clicking run on every cell. The program will store the following 
outputs in the folder where the program is being executed from.

  -CNN.png (plot for an CNN twitter sentiments)
  -BBC.png (plot for an BBC twitter sentiments)
  -FOX.png (plot for an FOX twitter sentiments)
  -CBS.png (plot for an CBS twitter sentiments)
  -NYTimes.png (plot for an New York Times twitter sentiments)
  -BBC sentiments.csv (sentiment data for BBC in excel format)
  -CBS sentiments.csv (sentiment data for CBS in excel format)
  -FOX sentiments.csv (sentiment data for FOX in excel format)
  -NYTimes sentiments.csv (sentiment data for New York Times in excel format)
  -CNN sentiments.csv (sentiment data for CNN in excel format)
  -SentimentAnalysisScatter.png(scatter plot for all media companies)
  -SentimentAnalysisBar.png(bar chart for all media companies)
  
