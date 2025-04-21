# Bitcoin Price Prediction

## Overview
This project aims to predict Bitcoin prices using social media sentiment analysis.

## Data Collection
- **Twitter Data**: Collected 1000 tweets from a Kaggle dataset (https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets) due to Twitter API access limitations.
- **Reddit Data**: Collected 100 posts from r/Bitcoin using PRAW.
- **News Data**: Collected 100 news articles using NewsAPI.

## Sentiment Analysis
- Performed sentiment analysis on Twitter, Reddit, and NewsAPI data using TextBlob.
- Added sentiment scores to the datasets, saved as `tweets_with_sentiment.csv`, `reddit_posts_with_sentiment.csv`, and `news_articles_with_sentiment.csv`.

## Directory Structure
- `data/`: Stores raw and processed data (tweets.csv, reddit_posts.csv, news_articles.csv, tweets_with_sentiment.csv, reddit_posts_with_sentiment.csv, news_articles_with_sentiment.csv).
- `notebooks/`: Jupyter notebooks for data collection and sentiment analysis.
- `src/`: Python scripts for utilities (currently empty).

## Next Steps
- Train a model to predict Bitcoin prices using sentiment scores.

