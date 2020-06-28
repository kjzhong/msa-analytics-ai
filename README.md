# MSA - AI & Advanced Analytics Submission

This is my submission for the first MSA module, AI & Advanced Analytics.

# Installation

In a fresh conda virtual environment:
```bash
conda env create -f environment.yml
conda activate analytics
```

# Project
This project uses a KNeighbors classifier to predict the species of flower given petal and sepal length and width.
Using 5 neighbors, the model achieved 100% accuracy. This is likely highly influenced by a small data set.

Future recommendations would be to implement other methods of model validation, such as k-fold cross-validation with more folds, LOOCV, or simply increase the number of observations in the dataset. There, is, however, a balance that should be struck.
