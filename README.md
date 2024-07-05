
<p align="center">

  <h2 align="center">Sentiment Analysis of Tweets with Emoticons</h2>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <li><a href="#paper-link">Paper Link</a></li>
    <li><a href="#abstract">Abstract</a></li>
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#dataset">Dataset</a></li>
      <li><a href="#models">Models</a></li>
      <li><a href="#results">Results</a></li>
</details>


## Paper Link
Paper: [Link](https://link.springer.com/chapter/10.1007/978-3-031-24848-1_15)

## Abstract
Social networking services allow users to communicate with their friends and exchange ideas, photos, and videos that delineate their feelings. Sentiments are emotions that express a person’s 
attitude, feelings, and worldview. This raises the possibility of analyzing individual moods and emotions in social network data in order to learn more about people’s inclinations and 
perspectives when communicating online.
Sentiment Analysis is the computational study of opinions, assessments, attitudes, subjectivity, and viewpoints represented in text. The emotive appraisal of a condition is a general evaluation 
of that condition that may be positive or negative depending on physical or mental reactions. In this paper, we attempt to evaluate tweets that contain both text and emoticons in order to 
determine whether they are positive or negative.
This study looked at XGBoost, LinearSVC, Logistic Regression, and BernoulliNB algorithms, with XGBoost providing the highest accuracy of 87.841%. The paper’s key contribution is the use of the 
XGBoost model for tweets that include emoticons, which also produced the greatest accuracy.

## Introduction
This project focuses on the sentiment analysis of tweets, particularly those containing emoticons, to determine if they convey positive or negative sentiments. The goal is to leverage machine 
learning models to achieve high accuracy in sentiment classification.

## Dataset
The dataset used in this study consists of tweets containing both text and emoticons. Each tweet is labeled as either positive or negative. The dataset is split into training and testing sets 
to evaluate the performance of various machine learning models.

## Models
We evaluated the following machine learning models for sentiment analysis:
1. XGBoost
2. LinearSVC
3. Logistic Regression
4. BernoulliNB

## Results
The performance of each model was evaluated based on accuracy. The XGBoost model achieved the highest accuracy of 87.841%, making it the best performing model for this task.

