# 🚀 Diabets - clustering

This repository contains research for diabets clustering use case.

Task is to predict whether an individual has diabetes or not.

The target is the Diabetes column.

It has three different values: 0, 1, 2.
- 0 means that the observed person is healthy,
- 1 means that there is a risk of diabetes,
- 2 means the presence of diabetes.

## DATA Review
We will use gender, number of years in the US, family income, and some indicators measured by medical professionals as indicators.

## Brief Overview of the Files:
### 1. requirements.txt
Before running code locally please install dependancies from requirements.txt

### 2. research/diabets_clustering.ipynb
Main research file

### Metrics: accuracy

### Pipeline:
1. EDA
2. K-means --> add cluster as a feature
4. Trained different models:
	- RandomForestClassifier
	- LogisticRegression
	- LinearSVC

As a result, the LinearSVC succeeded and gave the best predictions




