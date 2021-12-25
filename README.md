![GitHub top language](https://img.shields.io/github/languages/top/Thomas-George-T/Social-Media-Analytics-in-R?style=flat)
![GitHub language count](https://img.shields.io/github/languages/count/Thomas-George-T/Social-Media-Analytics-in-R?style=flat)
![ViewCount](https://views.whatilearened.today/views/github/Thomas-George-T/Social-Media-Analytics-in-R.svg?cache=remove)

# Social Media Analytics in R

Taking a look at data of 1.6 million twitter users and drawing useful insights while exploring interesting patterns. The techniques used include text mining, sentimental analysis, probability,time series analysis and Hierarchical clustering on text/words.

<br>

<p align="center">
	<a href="#">
		<img src="https://raw.githubusercontent.com/Thomas-George-T/Thomas-George-T/master/assets/r-lang.svg" alt="R Language" title="R" hspace=80 />
	</a>
</p>

## 1.1 Data Description

We use two different files in our data sets:

1. The *tweets.csv* data set contains 1.6 million tweets with 6 fields as follows:

- target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
- ids: The id of the tweet ( 2087)
- date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- flag: The query (lyx). If there is no query, then this value is NO_QUERY.
- user: the user that tweeted (robotickilldozr)
- text: the text of the tweet (Lyx is cool)

2. The *daily-website-visitors.csv* contains 5 years of daily time series data for several measures of traffic with 2167 records and 8 Columns:

- Row: Unique row number for each record
- Day: Day of week in text fomr (Sunday, Monday, etc)
- Day.Of.Week: (Day of week in numeric form (1-7))
- Date: Date in mm/dd/yyyy format
- Page.Loads: Daily number of pages loaded
- Unique.Visits: Daily number of visitors from whose IP addresses there haven't been hits on any page in over 6 hours
- First.Time.Visits: Number of unique visitors who do not have a cookie identifying them as a previous customer
- Returning.Visits: Number of unique visitors minus first time visitors

## 1.2 Data Acquisition

We acquire both the data sets from Kaggle:

1. https://www.kaggle.com/kazanova/sentiment140

2. https://www.kaggle.com/bobnau/daily-website-visitors

# 2. Analytical Questions 

## 2.1 Text Mining

- Finding the frequently used unique words
- Sentimental Trends of Tweets

## 2.2 Clustering Analysis

- Hierarchical clustering words by sentiments

## 2.3 Probability

- Calculating the Probability Mass Function (PMF) and Cumulative Distribution Function (CDF)
- Probability Mass Function over Time

## 2.4 Time Series

- Trend analysis for different sentiments for each day of the week.
- Trend analysis looking at number of tweets per day of the week
- RQA (Reccurence Quantification Analysis)
- Computing Degree of Permutation Entropy and Complexity
- Number of Tweets per day over a period of 3 Months

# 3. Report

After conducting our analysis with the available data, we visualize and answer all of the above Analytical questions and consolidate them into the following concise report: [PDF](https://github.com/Thomas-George-T/Social-Media-Analytics-in-R/blob/main/Social-Media-Analytics.pdf)

# 4. Summary

After careful analysis of 1.6 million worth of twitter data, We were able to decipher lot of emerging patterns and visualize them. We were able to gain valuable insights about our business questions through various plots,text analysis/mining, clustering, probability and time series data.
