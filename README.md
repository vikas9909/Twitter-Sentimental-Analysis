# Twitter-Sentimental-Analysis
This project focuses on entity-level sentiment analysis using Twitter data. It classifies tweets as Positive, Negative, or Neutral concerning specific entities. Includes preprocessing, training (BERT-based models), and evaluation scripts. Perfect for exploring NLP techniques in social media sentiment classification.
# Entity-Level Sentiment Analysis on Twitter Data

## Overview
This project focuses on entity-level sentiment analysis of Twitter data. Given a tweet and an entity, the task is to classify the sentiment of the tweet regarding the entity as Positive, Negative, or Neutral. Tweets not relevant to the entity are treated as Neutral.

## Dataset
We use the following datasets for this project:
- 'Twitter_Data.csv'

Each dataset contains columns for:
- `tweet`: The text of the tweet.
- `entity`: The entity being analyzed.
- `sentiment`: The sentiment of the tweet about the entity (Positive, Negative, Neutral).

## Features
- **Preprocessing**: Combining tweet and entity information, cleaning, and tokenization.
- **Model Training**: Using BERT-based models for state-of-the-art sentiment classification.
- **Evaluation**: Accurate sentiment classification with metrics like accuracy and a detailed classification report.


