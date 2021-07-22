# Twitter Sentiment Analysis
Author: Christopher Varghese

## Overview
This project is focused around accurately identifying positive, negative, or neutral sentiment in a Tweet. The necessary goals of this project are to:
- Acquire the data, in this case Tweets
- Clean the data so that it can be processed and vectorized for modelling
- Analyzing various features of the data
- Modelling the data using various classifiers and iterating better versions

## Business Problem
Twitter is one of the biggest social platforms to exist. Unlike its competitors such as facebook and instagram, the 'posts' on 
Twitter are small snippet messages, referred to as Tweets. These Tweets can often be categorized under a particular hashtag or contain key words 
that relate it to a certain topic. Therefore, developing a model that can extract sentiment from Tweets has a multitude of advantages for a business. 
First, it can be a tool to gather data on public opinion regarding a product or service. Second, it can be used to gather information on a competitors 
product or service. Moreover, applications extend into the political realm where public opinion is likely the greatest metric to guarantee success in 
an election. This project aims to give this leverage to the parties that are interested.

## Data Understanding
This data was obtained from data.world. It consists of 9,092 tweets that were labeled as positive, negative, neutral, or undetermined by real users. Each tweet 
has three associated columns: the actual tweet, the topic of the tweet, and the determined emotion. When all the tweets are combined after cleaning, there are 
106,471 total words and 7,796 unique words.

![sentiment dist for all emotions](resources/sentiment_dist_all.png)
