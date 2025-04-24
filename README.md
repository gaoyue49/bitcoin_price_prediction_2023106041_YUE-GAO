# Bitcoin Price Prediction Project (2023106041 YUE GAO)

## 프로젝트 개요 (Project Overview)
이 프로젝트는 비트코인 가격 예측을 위해 소셜 미디어 데이터를 분석하는 NLP 프로젝트입니다. Reddit과 Twitter 데이터를 수집하여 감정 분석, N-gram, TF-IDF 작업을 수행하고 결과를 시각화했습니다. 하드웨어 제약으로 인해 일부 결과는 시뮬레이션으로 대체되었습니다.

This project is an NLP project for Bitcoin price prediction by analyzing social media data. It collects Reddit and Twitter data, performs sentiment analysis, N-gram, and TF-IDF tasks, and visualizes the results. Due to hardware limitations, some results are simulated.

## 데이터 소스 (Data Sources)
- **Reddit Data**  
  - 파일: `reddit_posts.csv`  
  - 설명: Reddit에서 비트코인 관련 100개의 게시물을 Reddit API를 사용하여 수집했습니다. 데이터는 타임스탬프, 게시물 텍스트, 언어 정보를 포함합니다.  
  - Description: 100 Bitcoin-related posts collected from Reddit using the Reddit API. The data includes timestamps, post text, and language information.

- **Twitter Data**  
  - 파일: `tweets.csv`  
  - 설명: Twitter에서 비트코인 관련 1000개의 트윗을 Twitter API를 사용하여 수집했습니다. 데이터는 타임스탬프, 트윗 텍스트, 언어 정보를 포함합니다.  
  - Description: 1000 Bitcoin-related tweets collected from Twitter using the Twitter API. The data includes timestamps, tweet text, and language information.

- **Bitcoin Price Data**  
  - 파일: `combined_data.csv`  
  - 설명: 비트코인 가격 데이터 841행으로, 감정 점수를 포함합니다.  
  - Description: 841 rows of historical Bitcoin price data with sentiment scores.

## 코드 설명 (Code Description)
- **notebooks/collect_data.ipynb**  
  - 데이터 수집 및 전처리, 감정 분석, N-gram, TF-IDF 작업, 시각화를 포함합니다.  
  - Includes data collection, preprocessing, sentiment analysis, N-gram, TF-IDF tasks, and visualization.

- **Colab Link**  
  - [Colab Notebook](https://colab.research.google.com/drive/12AGFCoMncX6DDBlqTuzNGoELmLNQ2me2?authuser=0#scrollTo=SBDvtg3hoFwC)  
  - 실행 가능한 Colab 노트북 링크 (공유 권한: 링크가 있는 모든 사람이 보기 가능).  
  - A runnable Colab notebook link (shared with "Anyone with the link can view").

## 실행 방법 (How to Run)
1. **GitHub 저장소 클론**  
   GitHub 저장소를 로컬로 클론합니다:  
   Clone the GitHub repository to your local machine:  
