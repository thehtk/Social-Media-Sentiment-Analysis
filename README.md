# Social-Media-Sentiment-Analysis

This project focuses on analyzing sentiments from tweets using a machine learning approach. The dataset contains tweets labeled as either **positive** (label: 0) or **negative** (label: 1). The project implements data preprocessing, visualization, and classification techniques to build a sentiment analysis model.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Features](#features)
5. [Setup and Installation](#setup-and-installation)
6. [Usage](#usage)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

Social media platforms like Twitter enable people to express their opinions and share information. Analyzing these tweets can provide insights into public sentiment regarding various topics. This project cleans and processes raw tweet data, builds machine learning models, and evaluates their performance using metrics like F1-Score.

## Dataset

The dataset used in this project can be found [here](https://github.com/thehtk/Social-Media-Sentiment-Analysis).  
- **Training Data:** Contains labeled tweets for supervised learning.
- **Test Data:** Used for evaluation.

## Technologies Used

- **Languages:** Python
- **Libraries:** 
  - pandas, numpy, re
  - nltk, scikit-learn
  - matplotlib, seaborn, wordcloud
- **Tools:** Logistic Regression, Bag of Words (BoW), TF-IDF

## Features

### 1. Data Preprocessing
- Cleaning tweets by removing usernames, special characters, numbers, and short words.
- Tokenization and stemming using NLTK.
- Extracting hashtags for sentiment analysis.

### 2. Data Visualization
- WordClouds to visualize common words for positive and negative sentiments.
- Bar plots for the frequency of hashtags.

### 3. Machine Learning Models
- Logistic Regression for sentiment classification.
- Feature engineering using:
  - Bag of Words (BoW)
  - TF-IDF (Term Frequency-Inverse Document Frequency)


