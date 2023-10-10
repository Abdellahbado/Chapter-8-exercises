# Chapter-8-exercises
This repository contains my solutions to the exercises in Chapter 8 'Dimensionality reduction' of the book "Hands-On Machine Learning" by Aurélien Géron. The solutions are written in Python using the scikit-learn library. 
# MNIST Dataset and Dimensionality Reduction

In this repository, I've provided code and information for solving two exercises related to the MNIST dataset and dimensionality reduction using Python and scikit-learn. The exercises are as follows:

## Exercise 9: Random Forest Classifier and PCA

### Load and Split the MNIST Dataset
We start by loading the MNIST dataset, which contains handwritten digits, and split it into a training set (the first 60,000 instances) and a test set (the remaining 10,000 instances).

### Train a Random Forest Classifier
We then train a Random Forest classifier on the training set and measure the time it takes to train the model. After training, we evaluate the model's performance on the test set.

### Use PCA to Reduce Dimensionality
Next, we use Principal Component Analysis (PCA) to reduce the dataset's dimensionality while retaining 95% of the explained variance. This reduced dataset will be used to train a new Random Forest classifier.

### Train a New Random Forest Classifier
We train a new Random Forest classifier on the reduced dataset and measure the time it takes to train the model. After training, we evaluate the new classifier's performance on the test set and compare it to the previous classifier.

## Exercise 10: t-SNE for Dimensionality Reduction and Visualization

### Use t-SNE to Reduce the MNIST Dataset
In this exercise, we employ t-Distributed Stochastic Neighbor Embedding (t-SNE) to reduce the MNIST dataset to two dimensions. This reduction will help us visualize the dataset in a two-dimensional space.

### Plot the Result with Matplotlib
We plot the result of the t-SNE dimensionality reduction using Matplotlib. Each point in the scatterplot represents an instance from the dataset, and we use 10 different colors to represent each image's target class.


Please refer to the Jupyter Notebook or Python script in this repository for the code and detailed explanations for each exercise. Feel free to run the code and explore the results on your own!

If you have any questions or need further assistance, don't hesitate to reach out.

Happy coding!  
