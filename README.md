# Intersecting Social Media, Mental Health, and COVID-19: Predictive Analysis from Twitter Data

This repository houses the resources and findings of our research, which aimed to predict daily increases in COVID-19 confirmed and death cases using data from Twitter sentiments and mental health statistics.

## Overview
The goal of this research is to create predictive models using logistic and linear regression techniques. We designed a binary classification model (Logistic Regression) to determine whether the daily increase in confirmed/death cases is high or low when compared with the median daily increase number.

Next, we used a Linear Regression model to predict the exact daily increase case number. We utilized features such as sentiment scores and tweet counts related to COVID-19 and vaccines in these models.

## Data
The primary challenge was the extraction, cleaning, and aggregation of data from heterogeneous sources, particularly Twitter data and health statistics. We implemented Python's data analytical stack and SQL for data extraction and transformation to overcome this challenge.

## Models
We built logistic and linear regression models and incorporated features like sentiment scores and tweet counts related to COVID-19 and vaccines. To optimize our model's performance, we implemented regularization and feature engineering. Our models achieved a training accuracy of 75.55% and a testing accuracy of 67.24%.

## Results and Discussions
Despite the fairly satisfactory accuracies, we identified areas for model improvement, such as dataset extension and inclusion of additional features. We discussed the societal impacts and ethical concerns related to our study, such as user privacy and potential bias.

## Visualizations
Our research results include custom visualizations and dashboards that illustrate our findings and the performance of our models.

## Contribute
We welcome any contributions to improve our models or extend our datasets. Feel free to fork this repository, make changes, and create a pull request.

## Authors
Yunhua Su
Jinmeng Zhang
Yuqin Jiao
## Acknowledgments
We extend our gratitude to everyone who has contributed to this project, either by providing data or by offering their expertise and insights.
