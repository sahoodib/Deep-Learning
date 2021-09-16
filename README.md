# Deep-Learning(Solutions will be uploaded after december 2021)
This folder contains or will be containing all Deep Learning assignments
HW1:   S&P500 Index Prediction
The objectives of this homework are to (1) implement gradient descent by yourself and (2) get familiar with model selection.
Dataset:
Training data: SPY close prices of 2017-2020
Testing data: SPY close prices of Jan. 2021- Aug. 2021.
Problem formulation:  Given the previous N data points, you are going to predict the next value. n=1, ……, N.   N is a hyperparameter.
Model function: Linear function xt = f(xt-n, xt-n+1, …, xt-1)
Loss function: MSE
Find the best N. Report loss for both training and testing data from 1 to the identified N.  Show the values in a table and also plot them. For the best N, report the weights.
Suppose your best linear model is
xt’ = b2 * xt-2 + b1 * xt-1 + b0
You should report the best parameters, the function F and the value of N.
For example
xt’ = 0.83 * xt-2 + 0.54 *  xt-1 - 4.5 and N=2
