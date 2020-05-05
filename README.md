Handwritten Digit Recognition 
============================

This project uses the MNIST dataset to train an Artificial Neural Network using first principles to recognize handwritten digits. The neural net has 784 inputs (corresponding to 28x28 pixel images), 1 hidden layer with 25 units, and 10 output units, one per digit (0-9).

The MNIST dataset contains 60,000 training examples. This implementation purely based on first principles with no optimization, except for the gradient descent algorithm (scipy optimize). Therefore, training the ANN is slow. As a result, only 60% of the available data (36,000 examples) is used to train the network. Nonetheless, it achieves ~90% accuracy in predicting the training set.

A simple GUI is also included, allowing the user to write numbers using a mouse. A prediction is made using the optimized weights and bias values.

![GUI Animation](animation.gif)

This project builds on the assignments for the Coursera MOOC: [Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning).

A [csv version](https://www.kaggle.com/oddrationale/mnist-in-csv) of the MNIST data is used in this project. Credits for the csv file goes to [Dariel Dato-on](https://www.kaggle.com/oddrationale) on Kaggle.
