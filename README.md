# Deep-learning-with-more-than-one-Optimizer

The work mainly focused to evaluate the performance difference while utilizing different optimizers in the same model.

# CIFAR10 Dataset
Dataset consists of 60000 colour (r * g * b) training images and 10000 testing images of size 32x32 with 10 classes.
The classes are:
* Airplane
* Automobile
* Bird
* Cat
* Dog
* Frog
* Horse
* Ship
* Truck

# Libraries
* Tensorflow
* Matplotlib
* Numpy

# Activation functions
* relu
* softmax
* sigmoid

# Optimizer
* adam

# Summary
In the initial phase got 92% & 67 % of training, testing accuracy. Again the system tranined with the optimizer and got an higher improvement in the training set which gave 100% accuracy but still the testing set gave 68% accurate results. After that created another model for checking the results, here the no. of epochs are increased to 20 from 10. Here also got 100% accurate results in the traning set however, the testing set accuracy reamained 68%. From this found that, we can improve the testing accuracy with the help of more optimizers in the same model it will give the results what we will get from more epochs levels.

