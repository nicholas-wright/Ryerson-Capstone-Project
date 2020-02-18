# Stock Market Index Performance and Public Sentiment

### Outline

Public opinion has long held sway over company valuations, with a positive public opinion a company can be evaluated favorably and with a negative it can lose billions. In the past, our opinions were formed based on information consumed through the nightly news. This has now shifted to the internet, with more people engaging with the news through an organization’s website, than their nightly programing. The theme this paper explores is if a correlation exists between sentiments expressed on news websites and the overall performance of stock market indexes.

The research questions that will be addressed are; Do sentiments expressed by news sites have a correlation on a stock market index’s performance? And, is it possible to predict the daily or weekly shift in the index based on the sentiments expressed? 

Two datasets will be used to accomplish this. The first is the daily performance (5 attributes) of the Nasdaq, S&P 500, NYSE, Dow Jones and TSX indexes. This dataset encompasses the years 2015 - 2017. These datasets will be collected from Yahoo Finance historical data. The second dataset is a collection of 143,000+ headlines with 8 attributes, taken from 15 popular news sites (New York Times, CNN, Business Insider etc.). Sentiment analysis will be used to determine a positive (buy), negative (sell) or neutral (hold) stance. Once sentiment has been determined on the second dataset, the two datasets will be merged and ordered based on date. These three sentiments will then be used as classifiers to train a predictive model. Linear regression and time series analysis will also be used to discover significant features and trends within the amalgamated dataset.



