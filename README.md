![Alt text](https://s3.amazonaws.com/poly-screenshots.angel.co/Project/1a/639856/fdb2121c06e273d1e284f9e6509de99d-original.jpeg?raw=true "Finding Donors for CharityML")
# Finding_Donors_For_CharityML
In this project, I employed several supervised learning algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. Then I chose the best candidate algorithm from preliminary results and further optimized this algorithm to best model the data.
## Installation
For running this project, the most important library is Python 3 version of Anaconda Distribution. It installs all necessary packages for analysis and building models.
## Introducing the datasets
The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The datset was donated by Ron Kohavi and Barry Becker, after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". The data we investigate here consists of small changes to the original dataset, such as removing the 'fnlwgt' feature and records with missing or ill-formatted entries.
## File Description
### Readme
This file provides high level overview of the work done in project.
### Code
finding_donors.ipynb consists of the code required to load, clean, explore and visualize the data and answer the questions.
### Data
census.csv
### Supplementary
visuals.py 
### HTML Report
finding_donors.html provides python notebook in html format.
## Project Motivation
The goal is to help a non profit organization by constructing a model that accurately predicts whether an individual makes more than $50,000. This will help the organization to better understand how large of a donation to request, or whether or not they should reach out to begin with.
## Data Preparation
I applied logarithmic transformations to the highly-skewed feature distributions so that the very large and very small values do not negatively affect the performance of a learning algorithm. I also applied normalization to the features to ensure that each feature is treated equally when applying supervised learners. I converted categorical variables to binaries because typically the learning algorithms expect input to be numeric.
## Modeling, Optimization and Feature extraction
I applied and evaluated performance of these three supervised learning algorithms: Decision Tree, SVm and KNN.  I measured F score, training and prediction time for all of them to evaluate performance. I applied grid search to optimize the best of the three models. I also implemented AdaBoostClassifier model to find out most important features in predictiong the output variable. Reran the model on only the five most significant features.
## Result
KNN yielded the best F score although it took longest time for prediction. Grid search optimization improved the f score from 0.64 to 0.65. The model on reduced data (only 5 most significant features) reduced F score from 0.65 to 0.58.
## Acknowledgement
Thanks to Udacity Data Scientist Nanodegree content creators for providing us the opportunity to work on this project.
