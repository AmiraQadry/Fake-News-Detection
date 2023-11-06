# Fake News Detection

This project aims to detect fake news using a [PassiveAggressiveClassifier(PAC)](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.PassiveAggressiveClassifier.html). It analyzes textual content to identify misleading or false information.

## Dataset

The project uses a fake news dataset obtained from Kaggle. You can download the dataset from the following link: [Fake News Dataset](https://www.kaggle.com/datasets/hassanamin/textdb3).

The dataset consists of a CSV file named fake_or_real_news.csv, which contains labeled news articles. Each article has a "text" column containing the news content and a "label" column indicating whether the news is real or fake.

## Prerequisites

Make sure you have the following dependencies installed:

- Python (version 3.6 or higher)
- pandas
- numpy
- matplotlib.pyplot
- scikit-learn
