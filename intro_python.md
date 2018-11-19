## Overview

Welcome to the Research Computing Training Program, Module 2. This module will teach you the basics of python programming with a focus on applying them to the manipulation of data files. As in Module 1, you will be provided with basic training materials and links to resources that you will use in aid of a machine learning model from one of python's popular modules, sklearn. Understanding the inner details of how this model functions will be left to later, detailed sections on machine learning and AI. For this task it is sufficient to demonstrate knowledge of how to import data, basic cleaning, and report the results of a random forest model from [scikit-learn](https://scikit-learn.org/stable/) using the the [titanic dataset](https://www.kaggle.com/c/titanic).



## Required Tools

For a longer list of tools, please see the really quite good version established in [Module 1](https://avc.web.usf.edu/training/basic-web/). Notably, we will use Git for version control and something like Visual Studio Code for editing.

* Python 3 - Python 3 had a longer time than expected to get established, but at this point, most scientific code is moving over to python 3 and if you are learning python fresh there is no benefit to starting with python 2.

## Recommended 

* [Conda](https://conda.io/docs/) - Provides an easy package management system for python and related programs (can install things that aren't strictly python unlike pip). Provides optimized packages for scientific libraries like numpy, scikit-learn, pandas, etc.

# Deliverables

The overall project you will be expected to deliver is to go from the initial input files of the [titanic dataset](https://www.kaggle.com/c/titanic) from Kaggle and, after some basic [data cleaning](https://www.kaggle.com/thomasekeller/data-types-and-missing-data-workbook/edit) produce some results from a [random forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html). Machine learning and statistics often begins by understanding the type of data you are trying to predict. Here, the problem as defined from the kaggle website is "in this challenge, we ask you to complete the analysis of what sorts of people were likely to survive." This statements hints at a categorical dependent variable. An example of a numerical regression would be to look at say, the age at which a type of cancer occurs in the general population.

# Things to report

A few things that are usually looked for in a model, especially in machine learning, is how accurate it was. For random forests, this is typically provided with the [oob_score_](https://scikit-learn.org/stable/auto_examples/ensemble/plot_ensemble_oob.html) .

Second, giving a sorted list of the predictor variables with [feature importance](https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html) is also generally helpful and will be looked for.


# Resources

Most of your python learning will come in the form of working through [Jupyter notebooks](http://jupyter.org/) that form courses of Kaggle Learn.

* [Python , Kaggle Learn](https://www.kaggle.com/learn/python) There are a lot of extra fringe things you can do in python, but the lessons laid out here are a good starting point to writing solid code. Searching for "random forest" turns up many results.

* [Pandas , Kaggle Learn](https://www.kaggle.com/learn/pandas) Pandas is the main python library for data import and manipulation. This course is a series of notebooks on how to wrangle data to get it into a form that is amenable for downstream analysis.

* [Kaggle Kernels](https://www.kaggle.com/c/titanic/kernels) Looking at how other people have cleaned and analyzed this data is encouraged; however your code must be your own and you must be able to explain it.

* [Machine learning, Kaggle learning](https://www.kaggle.com/dansbecker/random-forests) *bonus* This example may be informative. However! Note that it is a separate dataset, and is for a Random Forest *Numerical Regressor*, rather than a Random Forest Classifier which is what we will use for our Titanic dataset. 

* [scikit-learn cheat sheet](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) decision tree of possible possible algorithms to use in scikit-learn dependening on your data (there are a lot)


