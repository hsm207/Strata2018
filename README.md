# Introduction

This repository contains code to reproduce the results described in my [How To Use Active Learning To Iteratively Improve Your Machine Learning Models](https://medium.com/towards-artificial-intelligence/how-to-use-active-learning-to-iteratively-improve-your-machine-learning-models-1c6164bdab99)
blog post. It borrows heavily from [this](https://github.com/Azure/Strata2018) repo.

# Prerequisites

* [Microsoft Machine Learning Server](https://www.microsoft.com/en-us/sql-server/machinelearningserver) to run the R code
* A [Databricks cluster] to run the [notebook](/text_classification/Word2Vec-pySpark-attack-comments-updated.ipynb) that creates the word embeddings (optional)

# Usage
Have a look at the [1_wiki_detox_active_learning_workshop](/text_classification/1_wiki_detox_active_learning_workshop.Rmd) notebook to reproduce all the results reported
in the blog post.

# Contributing
Feel free to raise a pull request if you have any questions, feedback, suggestions, etc.