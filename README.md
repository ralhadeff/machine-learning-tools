# machine-learning-tools
**A python implementation for machine learning tools**

*Written by Raphael Alhadeff, January-February 2019*

This repository will include all my machine learning implementations in python. The purpose of this implementation is for my own training, and does not aim at being fast.

Note: although some sections in the code could be improved for efficiency (e.g. more vectorization) one of my goals here was to make the code more instructive for a human reading it.

For the first few estimators (Linear and Logistic) I wrote a full support to pandas DataFrames and Series. I did not always implement this because there was no more new code to write and learn from by continuing this support. Generally speaking, using DF.values or Series.values should work for all numerical data.  
  

General tools that are in specific folders (other folder names are self-explanatory):
 * _Regularization_ is in `LinearRegression` (and has not be implemented in the `LogisticRegression`)
 * _One-vs-rest_ classification scheme is in `LogisticRegression`
 * _One-vs-one_ classification scheme is in `SVM`
 * `modules` contains _linear algebra_, _scaling_ tools, a _polynomial features generator_, and a _data splitting_ tool
 * _Validation curve_ is in `DecisionTrees`
