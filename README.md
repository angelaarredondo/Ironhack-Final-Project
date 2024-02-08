## Sentiment Analysis on L'oreal Active Cosmetics Line
### Final Project - Data Analytics Bootcamp

## Overview
Consumer's opinion has enormous power for company decision making. 
Therefore, for my Final Project of the Ironhack Data Analysis Bootcamp, I decided to analyze consumer opinions regarding the cosmetics range of L'oreal, a French multinational company leader in the cosmetics and beauty industry. Through Natural Language Processing, this will allow the company to know what percentage of users out of the chosen population have a positive or negative opinion about the brand, and the reasons that motivate them to think in a certain way.

## Procedure
### 1- Products Scraping and Tweepy 
To carry out the Sentiment Analysis, I scraped tweets from the last three years in which an opinion of each of the brands have been shown (January 2020 - January 2023). In total, approximately 100,000 tweets were obtained. The tecniques used fot this first step were:
- Web Scraping
- APIS: Tweepy

### 2- Ngram Analysis
Afterwards, I proceeded with the Sentiment Analysis. For this purpose, I conducted an #Ngram Analysis, a powerful tool that can be used by businesses to gain insights into trends and patterns in language use. The tecniques used were:
- Data Cleaning (Numpy, Pandas)
- NLTK and Sklearn libraries

### 3- LDA Models
Finally, I went further and used a machine learning model that takes sentiment analysis to another level. This is #LDA (Latent Dirichlet Allocation) analysis, a machine learning technique that is commonly used for topic modeling. Library used:
- pyLDAvis

Check the code for further details.
