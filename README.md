# Machine Learning Project Overview

This project encompasses a series of exercises designed to apply and enhance machine learning skills. It covers various aspects of machine learning, from fundamental concepts to advanced techniques, including cross-validation, regression analysis, k-NN algorithms, and text processing with Naive Bayes classifiers.

## Getting Started
To get started, clone this repository to your local machine. Ensure you have Python installed along with the necessary libraries specified.

## Project Structure
The project is divided into four main problems, each focusing on different machine learning concepts and techniques.

## Problem 1: Exploration
### Objective
Explore and understand new concepts not covered in class but closely related to the course material. Provide answers to three questions in 1.txt.

### Tasks
**a.** Discuss the differences between k-fold, leave one out, and random subsampling cross-validation algorithms. 
**b.** Explain the differences among Gaussian, Multinomial, and Bernoulli Naive Bayes methods. 
**c.** Define "linear separability." Discuss if data grouped into more than two clusters can be linearly separable. 


## Problem 2: Regression 
### Objective
Perform polynomial regression on the provided dataset funky.csv, exploring polynomial degrees from 1 to 6.

### Tasks
**a.** Implement polynomial regression and generate two plots: one showing the data points with regression curves and another showing the cost function's dependence on the polynomial degree. 
**b.** Train polynomial regression with degree 3 and L2 regularization, testing various lambda values. Generate similar plots to part a, discussing the effects of regularization. 



## Problem 3: k-NN 
### Objective
Use the spaceship-titanic.csv dataset to apply the k-NN algorithm, focusing on feature selection and parameter tuning.

### Tasks
**a.** Split the dataset, preprocess, and apply the unweighted version of k-NN considering only RoomService and FoodCourt features for k=15. Generate a plot showing classified areas by color. 
**b.** Experiment with k values from 1 to 50 using the same features, and plot the accuracy metric's dependence on k. Discuss the best k value. 
**c.** Include all features from the original dataset and compare the results with those obtained using selected features. 


## Problem 4: Text Processing / Naive Bayes 
### Objective
Classify tweets from the disaster-tweets.csv dataset using Multinomial Naive Bayes, achieving at least 65% accuracy.

### Tasks
**a.** Clean the dataset, create feature vectors, split the data, and fit a Multinomial Naive Bayes model. 
**b.** Identify and discuss the five most common words in positive and negative tweets, and calculate the LR metric for words, discussing the findings. 


## Running the Exercises
Each problem has associated Python scripts (2a.py, 2b.py, 3a.py, etc.) that can be executed to perform the tasks and generate the required outputs.










