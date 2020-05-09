# Hackathon: Census Income Predicto

<br>
<br>

> Mariam Javed <br>
> Aman Hafez <br> 

<a name="problem-statement"></a>
## Overview

The purpose of this hackathon is to create the best performing model on a hold-out sample of data, however, with a constrained optimization. To understand what that means, let's take a look at the [Project Management Venn Diagram](https://berkonomics.com/wp-content/uploads/2015/11/goodfastcheap1-1.png).

The idea is that for any project you can have any two of these. You can have good work done cheap, but it will take a long time. You can have good work done fast, but it won't be cheap. Or you can have work done fast and on the cheap, but it won't be good. For this project, my team was assigned the 'cheap' constraint where we had the choice to use whatever algorithm we wanted, whatever features we wanted, but were restricted to using the cheap data which was a significantly small dataset (6000 rows).


## Project statement

Using the [1994 Census bureau](https://archive.ics.uci.edu/ml/datasets/adult) database by Ronny Kohavi and Barry Becker, predict if a person's income is in excess of 50K given certain profile information. More specifically, generate predicted probabilities of income being above 50K for each row in the test set. The constraint that our team was assigned was: the 'Feature' constraint where we must use the 'cheap' train sample dataset.


## Executive Summary

Our constraint for this hackathon project was working with a cheap dataset, a dataset of just over 6000 rows, and testing on a hold-out dataset that was over 16000 rows. We trained the following 4 models:

- Logistic Regression
- KNN
- Random Forest
- SVM

We were able to develop an accurate Logistic Regression model that predicts the wage for individuals from the Census dataset. The Logistic Regression model preformed the best out of all models that were tested; it returned the highest and most consistent accuracy score of 0.848 and 0.841 for training and validation respectively, highest f1 score of 0.639, and an AUROC score of 0.9. Some of the variables that are a good predictor of wage are: education, hours worked per week, and age.






