# COMP551(Fall-2019)-Applied Machine Learning 
# Mini Project 2 (Subreddit Classifier)
### Contributors: Shantanil Bagchi, Nikhil Podila, Manoosh Samiei

## Abstract
In this project, we investigate the performance of text classiﬁcation methods on reddit posts from over 20 subreddits. We preprocess the data using natural language processing techniques such as stopword removal, TF-IDF weighting, χ2 test for feature selection. We used various classiﬁcation algorithms and found that an Ensemble Classiﬁer performed the best on this dataset. We also implemented Bernoulli Naive Bayes from scratch. Performances of all the classiﬁers and our implementation of Bernoulli NB are compared on the dataset. We achieved an accuracy of 61.02% on held-out validation set and 58.633% on Kaggle test set

## Repository Structure
The repository contains following files:

* 1 Jupyter notebook files - COMP551 (Fall 2019) Applied Machine Learning Mini Project 2 (Subreddit Classifier).ipynb
* 2 Dataset files - reddit_train.data and reddit_test.csv
* 1 ReadMe file - ReadMe.md
* 1 Project writeup - writeup.pdf
* 1 Libraries file - requirements.txt

## Code Usage - (Python 3.6.2, conda 4.3.23)
1. Install required python libraries from requirements.txt
(refer to https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1 for steps to install libraries using requirements.txt)
2. Download all Jupyter notebook and Dataset files into one directory.
3. Open Jupyter notebook into that directory.
4. Select the required notebook (.ipynb file) and select "Run All" inside the jupyter notebook file.

## Packages
The following packages were used in the code:

* sklearn, numpy, pandas, time, re, scipy, itertools, seaborn, matplotlib, nltk, tqdm, gensim, pyLDAvis, logging, pprint, wordcloud, spacy
