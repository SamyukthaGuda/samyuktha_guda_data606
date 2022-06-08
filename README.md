# UMBC DATA606 Data Science Capstone Project

# Capstone Project Proposal

# STOCK TREND PREDICTION USING SENTIMENT ANALYSIS

Team Mates : Samyuktha Guda, Samyuktha Jalagam, Nikhitha Alla

**What is your issue of interest (provide sufficient background information)?**

The stock market is a major topic in modern life. Investors can easily purchase new stocks and gain significant profits from dividends provided in the company’s bonus program for shareholders. Investors can also trade their own stocks with the other traders in the stock market via stock brokerages and electronic trading platforms. The stock exchange reflects market capitalism, and millions of stocks are traded every day. Stock movement prediction has attracted many researchers in multiple disciplines, including computer science, statistics, economics, finance, and operations research. These are based on long-term and short-term market trading activities that reflect different trading patterns. Our aim is to analyze one of those trading patterns called intraday trading. Intraday trading is highly dependent on the news about a specific stock on a given day. Our prime goal is to look at how sentiment analysis on stock news affects stock movement. With significant breakthroughs in data science and machine learning, today, we have different techniques to analyze almost all forms of data available.

**Why is this issue important to you and/or to others?**

I made an investment in stocks a couple of years ago and have incurred loss. That's when I understood that knowing how to anticipate the future economy, even if one don't trade stocks for a living or have any financial background, may be extremely beneficial to ones financial status. Stock price prediction assists one in determining the future worth of a company's stock and other financial assets traded on an exchange. The whole point of stock price forecasting is to make a lot of money. Stock price prediction is very much helpful in taking investment decisions.

**What questions do you have in mind and would like to answer?**

Why is stock trend prediction important?
How does sentiment analysis help in predicting the trends in stock market?
Stock market prediction aims to determine the future movement of the stock value of a financial exchange. The accurate prediction of share price movement will lead to more profit investors can make. If the news sentiment is favorable, the stock price is more likely to rise; if the news sentiment is negative, the stock price is more likely to fall. Sentiment Analysis can forecast news polarity, which can influence stock market patterns.

**Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?**

We will be considering two datasets for exploring and analyzing the stock movement, daily financial news from Kaggle, and the stock market daily data from Yahoo Finance by 'pandas_datareader.web'. 

Dataset 1 contains 221,504 rows and 9 columns and the size of the data is 273 MB

Dataset 2 contains 799851 rows and 8 columns.

Attributes include:

id: Auto-incremented count of order when the item was collected

ticker: A ticker symbol or stock symbol is an abbreviation used to uniquely identify publicly traded shares of a particular stock

title: News headline

category: Type: news or analysis/opinion

content: News body

release_date: Date of news release, has no time of a day

provider: Attribution to the content author. Name of a source of the content

URL: Link to the original source of the content

article_id: Unique identifier of the article assigned by investing.com website

**What will be your unit of analysis (for example, patient, organization, or country)?**

The Unit of analysis here is an Organization and my units of observation are sentiment of twitter tweets.

**What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?**

I would like to look at sentiment scores and yahoo financial information like impact on stock prices, polarity of financial news, and more.

**What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?**

In this project, the Machine Learning tools we plan to use to analyze the stock market are Valence Aware Dictionary for Sentiment Reasoning (VADER) with different classification models like
KNN
Decision tree
Random forest 
SVM
Logistic Regression 
Gaussian Naive Bayes

**How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?**

We are planning on using Sentiment analysis with VADER and various ML algorithms like KNN, Decision Tree, Random Forest, SVM, Logistics Regression, and Gaussian Naive Bayes to determine which algorithm has the highest accuracy in predicting the stock movement. The main reason we would like to use VADER is that it not only extracts sentiment but also tells us about how positive or negative the sentiment is. 

**What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practical applications, etc)?**

In this project, we are planning to perform sentiment analysis on the news and opinions published by different financial news websites. Later, we will be training the highest accuracy model among all the models used by combining stock data with news sentiment in order to predict the stock movement.

