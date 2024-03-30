# Data Preprocessing and Feature Engineering.
## How do you select data?

- Consider what data you actually need to address the question or problem you are working on. Questions to help think:
1 - What is the extent of the data you have available?
2 - What data is not available that you wish you had available?
3 - What data don't you need to address the problem?

### Better data > Fancier algorithms
- Formatting: selected data may not be in a suitable format
- Cleaning: Removal or fixing of missing data
- Sampling: More selected data availabel then needed

----

## Dummy Variables

- Transforming categorical attribute to numerical attribute
- Each attribute will have value either 0 or 1
- full Dummy variables:
- Dummy variables with reference group:
- Dummy variables for ordered categorical variable with refernce group:

----

## Transform Data

## Transformed attributes :  Box-Cox
----

# How to Handle missing data?
- no good way to deal with missing data!
- Different solutions for data imputation depending on the kind of problem.

## Data imputation 
- Mean / Median
- Zero / Constant values (most frequent)
- k-NN (k nearest neighbours is an algroithm that is used)
- Multivariate imputation (filling the missind data multiple times)
- Data Reduction (Feature selection, Instance selection, Discretization)
- Prinipal Component analysis
- Correlation
- Transform Data (Scaling, Decomposition, Aggregation)
- standardization (variance scaling) Resulting scaled feature has a mean of 0 and a variace of 1
- Min - Max Scaling

## Why scaling KNN?

## Features Engineering

coming up with feature is difficult, time-consuming, requires expert knowledge. Applied machine learning is basically feature engineering.

The features you use influence more than everything els the result. No algorithm alone, to my knowledge, can supplement the information given by the correct feature engineering.

data my be hard to understand and process. conduct feature engineering to make reading of the data easier for our machine learning models.

features engineering is a process of transformation the given data into a form which is easier to interpret.

----
## Iterative process of feature engineering

- Brainstorm features:
- Devise features:
- Select features:
- Evaluate models:

---

## Summary

step 1: Data Selection
step 2: Data pre-processing
step 3: Data transformation