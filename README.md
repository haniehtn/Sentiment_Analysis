# Sentiment_Analysis

# Goal

This project aims to automatically detect abusive comments in the comment sections of an online marketplace. The input dataset is provided by [Digikala](https://www.digikala.com/), which is the largest e-commerce platform in the Middle East [1]. The dataset is supervised as it contains the manual verification status of the comments. The goal is to find the best statistical model to make the verification process automatic.

# Approach

The data is normalized, tokenized, stemmed, and lemmatized in the pre-processing step to obtain a clean dataset. We then train a Naive Bayes model to classify the words with the probability of each word to be abusive as a target and the records of that word as a feature. The classification is binary as we aim to classify words into two categories: 1) abusive, 2) non-abusive.

# Results

The results of this experiment can be found in `BachelorProject.ipynb`. We conclude that a Naive Bayes model is the best fit for this task.	


[1] [https://en.wikipedia.org/wiki/Digikala](https://en.wikipedia.org/wiki/Digikala)
