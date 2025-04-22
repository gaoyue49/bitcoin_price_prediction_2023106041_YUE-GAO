# Bitcoin Price Prediction

## Overview
This project aims to predict Bitcoin prices using social media sentiment analysis.

## Data Collection
- **Twitter Data**: Collected 1000 tweets from a Kaggle dataset (https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets) due to Twitter API access limitations.
- **Reddit Data**: Collected 100 posts from r/Bitcoin using PRAW.
- **News Data**: Collected 100 news articles using NewsAPI.
- **Price Data**: Collected Bitcoin historical prices from 2023-01-01 to 2025-04-21 using yfinance.

## Sentiment Analysis
- Performed sentiment analysis on Twitter, Reddit, and NewsAPI data using TextBlob.
- Added sentiment scores to the datasets, saved as `tweets_with_sentiment.csv`, `reddit_posts_with_sentiment.csv`, and `news_articles_with_sentiment.csv`.

## Data Integration
- Merged sentiment scores with Bitcoin price data, saved as `combined_data.csv`.

## Model Training
- Trained a linear regression model to predict Bitcoin prices using sentiment scores from Twitter, Reddit, and NewsAPI.

## Directory Structure
- `data/`: Stores raw and processed data (tweets.csv, reddit_posts.csv, news_articles.csv, tweets_with_sentiment.csv, reddit_posts_with_sentiment.csv, news_articles_with_sentiment.csv, btc_prices.csv, combined_data.csv).
- `notebooks/`: Jupyter notebooks for data collection, sentiment analysis, and model training.
- `src/`: Python scripts for utilities (currently empty).

## Next Steps
- Improve model performance by using more advanced models like LSTM.
- Evaluate model performance using additional metrics like MAE and R².
