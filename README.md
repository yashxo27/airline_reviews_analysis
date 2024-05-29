# airline_reviews_analysis_and_prediction

## 01_webscrapping.ipynb & reviews.csv
It consists of python code where
  - Scraping is done of Airline Reviews, Customer Ratings and Recommendation from the website www.airlinequality.com
  - It uses BeautifulSoup and Requests for webscraping
  - It scrapes the latest 1000 Reviews present on the website
  - Generates reviews.csv

## 02_datacleaning.ipynb & cleaned_data.csv
It consists of python code where 
  - the cleaning of airline reviews for each customer in reviews.csv
  - It uses pandas, matplotlib and re for cleaning
  - It cleans all textual data, modifies columns, removes all null values and eliminates redundant columns
  - Generates cleaned_data.csv

## 03_sentiment_analysis.ipynb & sentiment_data.csv
It consists of python code where 
  - sentiment analysis is done for the "Reviews" data contained in cleaned_data.csv
  - It uses libraries like pandas, numpy, matplotlib, seaborn, nltk, statsmodels, transformers and scipy 
  - Sentiment Analysis is done using two approaches: 1) Vader Sentiment Scoring
                                             2) RoBERTa Model Huggingface
  - Both approaches have been compared to understand results
  - It contains visualisations which effectively potray insights

## 04_eda.ipynb & 05_pivot_tables.xlsx
It consits of
  - ipynb file and excel file both explore the data in different ways to present different insights
  - Exploratory Data Analysis of the Ratings left by the customer for each review
  - It contains visualisations which effectively potray insights
