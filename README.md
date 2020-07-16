# Neural-network-from-scratch
Neural Network from scratch using easy to understand python Object Oriented Programming

Goal of this project is to implement Multilayer Neural Network from scratch using numpy and python OOP.
This project only uses the sigmoid activation function. 
Want to add more activation functions to this project.

An object of class Neural network is created using numpy arrays x and y as input.
each column of x represents one training example. and each column of y is the corresponding output(one hot encoded).
You may use any data set of your liking to train and test this model.

Following is outline of the Implementation of Neural Network :
1. Hidden Layer Class - this class creates an object which stores all the wights and activations of all neurons in that layer.
2. Final Layer class - This class is inheritated from the Hidden Layer class and it has an additional function to calculate error.
3. First hidden layer takes X as an input tesnor of order 2 and each subsequent layer takes activations in the previous layer.
4. The final layer takes an additional input tensor Y(one hot encoded), to calulate error.
5. Each neuron uses only a sigmoid activation function. 
6. Cross entropy loss function has been used for loss finding.
6. Gradient Discent is used for optimization.
7. Input can be fed in batches for using stochastic gradient descent.



