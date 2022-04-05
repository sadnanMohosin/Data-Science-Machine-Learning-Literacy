# Data Preparation

## Insufficient Data
* No great solutions for insufficient data. Simply need to find more data sources
### Dealing with insufficient data
1. choose simpler model : 
   * with fewer parameters
   * e.g. Naive bayes,logistic regression
   * enseble learning
2. Transfer Learning : Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example, knowledge gained while learning to recognize cars could apply when trying to recognize trucks.

3. Data Augmentation : 1. increase the number of trainning samples 2. perturbed images are a form of data augmentation
4. Systhetic data :Artificially generate samples which mimic real world data. 
**Oversampling of existing data points 
Can introduce bias in existing data.**


## Too much data
Data might be excessive in two ways
- Curse of dimensionality: Too many 
columns 
- Outdated historical data: Too many 
rows


1.Outdated Historical Data:
If not eliminated, leads to concept drift 
Outdated historical data is a serious 
issue in specific applications
- Financial trading 
Usually requires human expert to judge 
which rows to leave out
 
Concept Drift:

The relationship between features (X-variables) and 
labels (Y-variables) changes over time; ML models fail 
to keep up, and consequently their performance suffers

2.Curse of Dimensionality:
- Feature selection: Deciding which 
data is actually relevant 
- Feature engineering: Aggregating 
very low-level data into useful 
features 
- Dimensionality Reduction: Reduce 
complexity without losing information.

Concept Hierarchy:

A mapping that combines very low-level features (e.g. 
latitudes and longitudes) into more general, usable 
features (e.g. zip codes)





## Dealing with missing values


## Dealing with outliers

* identifying outliers
   * Distance from mean
   * distance form fitted line 

points that lie more than 3 standard deviations from the mean are ofen considers as outliers
* coping with outliers
   * drop
   * cap/floor
   * set to mean

## Oversampling and Undersampling

## Overfitting and underfitting




