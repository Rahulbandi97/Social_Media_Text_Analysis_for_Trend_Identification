Social Media Text Analysis for Trend Identification

Overview

This project analyzes social media text to identify trends using Machine Learning (ML) and Deep Learning techniques. The datasets include Twitter and YouTube data, and the models range from traditional Logistic Regression to advanced BERT and RoBERTa transformers.

Features

Twitter Trend Analysis using TF-IDF & Logistic Regression

YouTube Trend Identification using BERT & RoBERTa

Performance Metrics: Accuracy, Precision, Recall, F1-score

Visualization: WordCloud, Data Distribution

Technologies Used

Languages: Python

Libraries:

pandas, numpy, sklearn, nltk, wordcloud

tensorflow, torch, transformers

Machine Learning Models: Logistic Regression, BERT, RoBERTa

Tools: Google Colab

Project Structure

Social_Media_Text_Analysis_for_Trend_Identification/
│── Twitter_Analysis/
│   ├── SocialMediaTextAnalysisTwitter.ipynb
│── Youtube_Analysis/
│   ├── SMTAYoutubeBERT.ipynb
│   ├── SMTAYoutubeRoBERTAa.ipynb
│── README.md

Installation & Setup

Clone the repository:

git clone <repo_url>
cd Social_Media_Text_Analysis_for_Trend_Identification

Install dependencies:

pip install pandas numpy nltk sklearn wordcloud torch transformers tensorflow

Run Jupyter Notebooks using Google Colab or locally with:

jupyter notebook

Usage

Twitter Analysis

Load dataset from GoogleDrive/MyDrive/SocialMediaTrendAnalysisDatasets/BollywoodTweets/tweets1m.csv

Perform preprocessing (Tokenization, Stopwords Removal, Stemming)

Extract features using TF-IDF

Train and evaluate Logistic Regression model

Generate WordCloud for trend visualization

YouTube Analysis

Load dataset from GoogleDrive/MyDrive/SocialMediaTrendAnalysisDatasets/YoutubeTrends/USvideos.csv

Preprocess data: Text Cleaning, Label Assignment (Trending or Not)

Train BERT / RoBERTa models for classification

Evaluate results using Accuracy, Precision, Recall, F1-score

Results

Logistic Regression achieved competitive accuracy on Twitter trends

BERT & RoBERTa effectively classify YouTube trending videos

Visualization techniques help in understanding trend patterns

Contribution

Feel free to contribute by improving models, adding new datasets, or optimizing performance. Fork the repo and submit a PR!

License

MIT License
