# FakeNews-Identification
Develop a machine learning program to identify when an article might be fake news. 
In this project, I have used various machine learning algorithms to classify fake news articles using sci-kit libraries from python.

## Prerequisites
1. Python 3.6.
2. You will also need to download and install below packages after you install either python or anaconda.
Sklearn (scikit-learn)
numpy
pandas
Regex
scipy
pandas_profiling
matplotlib

## Dataset used
Source: https://www.kaggle.com/c/fake-news/data

The dataset consists of 3 CSV files: "train.csv", "test.csv" and "submit.csv".
"train.csv" contains following columns

"id" of article
"Title" of the article
"Text" of the article
"Author" of the article
"Label" of article
1: fake
0: real

"test.csv" contains the same attributes as "train.csv", but without the "label" attribute. 
Prediction has been performed on these articles.

