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
