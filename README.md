# Sentiment Analysis for Movie Reviews
This repository contains code and resources for performing sentiment analysis on movie reviews using machine learning techniques.

## Overview
Sentiment analysis is the process of determining whether a piece of text is positive, negative, or neutral. This project focuses on analyzing the sentiment of movie reviews. The goal is to classify each review as either positive or negative.

## Dataset
The dataset used for this project consists of movie reviews along with their sentiment labels (positive or negative). The dataset can be obtained [here](https://www.kaggle.com/datasets/darshan1504/imdb-movie-reviews-2021/data).

## Installation
To run this project, you'll need to have Python installed along with several Python packages. You can install the necessary packages using:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
## Usage
1. Clone this repository:
```
git clone https://github.com/guccigauth/AISCSentimentAnalysis.git
cd AISCSentimentAnalysis
```
2. Run the Jupyter Notebook:
```
jupyter notebook sentiment_analysis_movie_reviews.ipynb
```
## Evaluation
The input data can be visualized in multiple ways such as:
1. word cloud
2. bar graph
3. pie chart

## Model Training
The notebook sentiment_analysis_movie_reviews.ipynb contains all the steps for training the sentiment analysis model. It includes:

1. Data preprocessing
2. Feature extraction
3. Model training using various algorithms
4. Hyperparameter tuning

## Results
The results section in the notebook displays the performance metrics and visualizations for the trained model. You can see how well the model performs on the test data.
