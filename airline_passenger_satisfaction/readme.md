## Exploration of features that affect airline passenger satisfaction

**Table of Contents**
1. EDA and Preprocessing
2. K-Means
3. PCA
4. Simple Logistic Regression
5. Summary

**Data Source**
- Kaggle [https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/data]
- Data provided has been split into train and test.

**Introduction**
- This is an optional assignment for CSE-6040 course. My objective is to explore concepts and tools used in the module to *understand what features affect airline passenger satisfaction most*.
- I will first do simple EDA and preprocessing, then K-means and PCA for unsupervised learning to analyse patterns and feature importance, and finally try simple logistic regression on both basic features and PCA transformed features.
- My preliminary hypothesis is that flight delays are the main factor due to the inconvenience and stress caused, followed by travel class (business or economy).

**Findings**
- K-means and PCA managed to group features into broad inflight experience and pre/post flight convenience categories.
- From K-means and PCA, it seems that inflight experience as well as pre/post flight convenience all play a big part in the flight experience. There is *no one single* important factor.
- Flight delays are lower in importance than expected.

**Limitations**
- Cost of travel was not considered here. It could be that passengers are satisfied with the service for the cost they pay (e.g. cheaper economy tickets).

**Further works**
- More detailed EDA
- Experimentation of dropping / manually combining features as hinted by PCA (e.g. cleaniness, in-flight entertainment etc)
- Other unsupervised learning e.g. hierarchical clustering or other models e.g. SVM, Random Forest
- Cross validation and tuning of hyperparameters, including random search tuning of PCA number of dimensions.

