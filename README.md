# MSA - AI & Advanced Analytics Submission

This is my submission for the first MSA module, AI & Advanced Analytics.

# Project
This project uses a KNeighbors classifier to predict the species of flower given petal and sepal length and width.
Using 5 neighbors, the model achieved 100% accuracy. This is likely highly influenced by a small data set.

Future recommendations would be to implement other methods of model validation, such as k-fold cross-validation with more folds, LOOCV, or simply increase the number of observations in the dataset. There, is, however, a balance that should be struck.

# Installation

With conda installed:
```bash
conda env create -f environment.yml
conda activate analytics
```
The primary modules used in the project are:
* pandas
* sklearn
* matplotlib
* seaborn
* numpy

# Instructions on how to train/test the model
1. Split the dataset into predictor and target variables 
2. Create train-test split with test\_size = 0.2 and random\_state = 42
3. Create your knn model with 5 neigbors
6. Train and test
