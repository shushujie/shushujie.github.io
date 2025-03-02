---
<<<<<<< HEAD
title: *
=======
title:
>>>>>>> 8805b4fd7aec2f53f1cfc5adddd775d56f35f940
layout: page
---











##

----------------------
This project focuses on the oxidation of tungsten. The rate constant of oxidation contains the implicit information about the parameters like the unit cell type, atmosphere, molecular electronic properties, oxidation temperature, time, oxidation conditions, alloy composition. There are many papers that discuss W0s oxidation process, and categorized data are also provided like temperature, time duration, growth conditions(like O2 concentration ), constituent phase etc. These datas can be constructed into a data set and will be nice to do a machine learning model. Using existing ML algorithms, it will be feasible to predict the parabolic rate constant of the oxidation process.

## What it does
While the people usually use the mass gain (or corrosion rate constant kP ) change to evaluate the oxidation process, it is rational to build a machine learning model to do the predict that.


## How we built it

In this project, we employed four different regression models: Gradient Boosting (GB), Random Forest (RF), K-Nearest Neighbors (KNN) and Multi-Layer Perceptron (MLP). For all four models, we directly imported the corresponding model from scikit-learn package, and we also implemented our own version of MLP using PyTorch. For the two versions of MLP (scikit-learn- based and PyTorch-based), they all have three layers with hidden layer sizes of 128 and 64, stochastic gradient descent (SGD) optimizer and mean-squared-error (MSE) loss are employed for model training.

## Challenge we ran into


With the model built, we can even expand the model to include composition of W0s alloys as one of the input parameters into the prediction model. According to the best of our knowleadge, we should be the first to do ML predictions for W oxidation (there are a couple of works to do it for steel and Ti).
