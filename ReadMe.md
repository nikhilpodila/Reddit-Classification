# Linear Classification - Red wine and Breast Cancer datasets
### Contributors: Shantanil Bagchi, Nikhil Podila, Surya
### Mini-Project 1 - COMP 551 Applied Machine Learning - McGill University

## Abstract
In this project, we investigate the performance of text classiﬁcation methods on reddit posts from over 20 subreddits. We preprocess the data using natural language processing techniques such as stopword removal, TF-IDF weighting, χ2 test for feature selection. We used various classiﬁcation algorithms and found that an Ensemble Classiﬁer performed the best on this dataset. We also implemented Bernoulli Naive Bayes from scratch. Performances of all the classiﬁers and our implementation of Bernoulli NB are compared on the dataset. We achieved an accuracy of 61.02% on held-out validation set and 58.633% on Kaggle test set. 

## Repository Structure
The repository contains 7 files:
* 1 Jupyter notebook file - PROJECT 2- FINAL.ipynb
* 2 Dataset files - reddit_train.csv and reddit_test.csv
* 1 ReadMe file - ReadMe.md
* 1 Project writeup - writeup.pdf

## Code Usage - (Python 3.6.2, conda 4.3.23)
1. Install the following libraries for Python (All the packages mentioned below can be installed using pip. <br>
In Jupyter notebook, use: !pip install <package_name>):

sklearn
numpy
pandas
time
re
scipy
itertools
seaborn
matplotlib
nltk
tqdm
gensim
pyLDAvis
logging
pprint
wordcloud
spacy


2. Download all Jupyter notebook and Dataset files into one directory.
3. Open Jupyter notebook into that directory.
4. Select the required notebook (.ipynb file) and select "Run All" inside the jupyter notebook file.



