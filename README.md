# Sentiment Yelpers - Yelp Review Sentiment Analysis

## Introduction

Welcome to Sentiment Yelpers' project repository! In this project, I delved into the analysis of sentiment in Yelp reviews, aiming to provide insights into public opinion on various businesses. I undertook a comprehensive exploration of sentiment classification utilizing a dataset of Yelp reviews.

## Dataset

I utilized a dataset consisting of Yelp reviews, which encompassed crucial attributes such as review ID, user ID, business ID, star ratings, and review text. My initial dataset comprised 20,000 rows of reviews, from which I derived sentiment labels categorized as negative (-1) for ratings ≤ 2, neutral (0) for a rating of 3, and positive (1) for ratings > 3.

### Exploratory Data Analysis

My journey began with exploratory data analysis, where I scrutinized the distribution of sentiments within our dataset. It was evident that a majority of our reviews leaned towards a positive rating, indicating an overall positive sentiment among Yelp reviewers.

Furthermore, I conducted extensive pre-processing of the review text, which involved converting text to lowercase, removing punctuation, and tokenizing the text into individual words. I curated a custom list of positive and negative words to aid in sentiment analysis, refining our dataset for subsequent analysis.

## Model Selection and Initial Performance

To gauge sentiment effectively, I evaluated the performance of three distinct classifiers: Gaussian Naive Bayes, Multinomial Naive Bayes, and Bernoulli Naive Bayes. Each classifier was chosen based on its aptitude in handling various data types, with a focus on their efficacy in text classification.

My analysis revealed nuanced differences in performance across classifiers, with the Multinomial Naive Bayes and Bernoulli Naive Bayes models exhibiting superior performance over the Gaussian Naive Bayes model. Through meticulous examination of training and testing error rates, I discerned insights into the models' suitability for sentiment analysis.

## Further Optimization of Selected Models

Building upon my initial findings, I explored further optimization techniques, including additive smoothing, to enhance the performance of the Multinomial and Bernoulli Naive Bayes models. Through experimentation with different hyperparameters, I identified optimal configurations that minimized error rates while maximizing predictive accuracy.

## Conclusion

In conclusion, my project encapsulates a thorough exploration of sentiment analysis in Yelp reviews, leveraging advanced techniques in natural language processing and machine learning. By meticulously analyzing error rates and model performance, I strived to provide valuable insights into public sentiment, thereby contributing to a deeper understanding of consumer perceptions in the Yelp ecosystem.
