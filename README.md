Based on the content from the provided document, here's a new README file that incorporates the information and structure specified, with content taken from the attached file:

---

![GitHub top language](https://img.shields.io/github/languages/top/Thomas-George-T/Social-Media-Analytics-in-R?style=flat?cache=remove)
![GitHub language count](https://img.shields.io/github/languages/count/Thomas-George-T/Social-Media-Analytics-in-R?style=flat)
![ViewCount](https://views.whatilearened.today/views/github/Thomas-George-T/Social-Media-Analytics-in-R.svg?cache=remove)

# Social Media Sentiment Analysis in R

Exploring insights from 1.6 million Twitter users by applying text mining, sentiment analysis, probability analysis, time series analysis, and hierarchical clustering to discover patterns and trends within the data.

<br>

<p align="center">
	<a href="#">
		<img src="https://raw.githubusercontent.com/Thomas-George-T/Thomas-George-T/master/assets/r-lang.svg" alt="R Language" title="R" hspace=80 />
	</a>
</p>

## 1.1 Data Description

The analysis utilizes two primary datasets:

1. *tweets.csv*: Comprising 1.6 million tweets, this dataset includes fields such as polarity (target), tweet ID, timestamp, query flag, user, and text content.
   
2. *daily-website-visitors.csv*: This dataset contains five years of daily traffic data, with metrics like page loads, unique visits, first-time visits, and returning visits, across 2,167 records.

## 1.2 Data Acquisition

Data for this analysis was sourced from Kaggle:

- Tweets dataset: [Sentiment140](https://www.kaggle.com/kazanova/sentiment140)
- Daily website visitors dataset: [Daily Website Visitors](https://www.kaggle.com/bobnau/daily-website-visitors)

# 2. Analytical Questions

## 2.1 Text Mining

### Finding Frequently Used Unique Words

Focus on extracting unique ideas by filtering out stop words, mentions, replies, and retweets, revealing the core content of tweets. The analysis shows "Day" as the most frequent word, followed by "Time", "Home", "Love", and "Night".

### Sentimental Trends of Tweets

Using the NRC lexicon, this part of the analysis identifies various sentiments in tweets, highlighting a balance among emotions like Anger, Disgust, and Surprise, and a notable presence of Fear and Trust sentiments.

## 2.2 Clustering Analysis

### Hierarchical Clustering Words by Sentiments

Employing hierarchical clustering on text data, this section generates a dendrogram to visualize word groups based on sentiment, choosing 12 clusters to best represent the data's sentiment structure.

## 2.3 Probability

### PMF and CDF of Tweet Frequency

Analyzing the distribution of tweet frequencies over time through Probability Mass Function (PMF) and Cumulative Distribution Function (CDF), noting a decreasing trend in tweet probabilities over a selected period.

## 2.4 Time Series

### Sentiment Trend Analysis

Evaluating sentiment trends across different days of the week, the analysis uncovers patterns in positive and negative sentiments, with weekends showing higher tweet activities.

# 3. Report

Our findings, drawn from comprehensive data analysis, are consolidated in a detailed report, accessible [here](https://github.com/BhaveshxPurohit/Analyzing-Social-Media-Sentiment/blob/main/Analyzing-Social-Media-Sentiment.pdf).

# 4. Summary

The project's analysis of 1.6 million tweets uncovers significant patterns and sentiments within social media discussions. Through diverse analytical techniques, it provides deep insights into user behavior and sentiment trends over time.

---

This README reflects the key aspects and structure of the provided content, tailored to encompass the specifics of the analysis described in the uploaded document.
