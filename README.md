# SOC_2024
####  This code is part of the assignment for the SOC project - "A Guided Tour to Pytorch" at IITB
####  Copyright of this project lies with IITB
## The Jupyter Notebook file that implements a neural network to perform binary classification on a set of images. 

### The flow of code is as follows:

#### a. The dataset of images is imported from Google Drive
#### b. All the necessary libraries for building the neural network are imported using PyTorch.
#### c. Then the data is sorted into train data and test data in conformity with neural networks algorithm.
#### d. Labels are added to the data to serve as target outputs for the ml model to predict and learn from during training.
#### e. The neural network is built as follows:
#####   (i)   The hyperparameters of the neural network are initialized.
#####   (ii)  A 3 layer neural network (i.e., 1 input layer, 2 hidden layers (10 and 12 nodes) and 1 output layer) is built. 
#####   (iii)  The Model includes the use of Linear function at each layer, alongside non-linear activation functions.
#####         (ReLU functions as activation functions for the input and hidden layers and Sigmoid function for the final output).
#####   (iv)  The loss_fn  is implemented as the Binary Cross Entropy Loss and the optimizer is the Stochastic Gradient Descent.
#### f. Adjusting the learning rate and the number of iterations is crucial for optimizing the training efficiency and performance of the model. 
#### g. The network takes around 5 minutes to finish training.
#### h. To quantize the accuracy of the network in the classification of images, a helper predict function is implemented.

#### End note: More experimentation can be done with the code like varying the number and size of the hidden layers and checking the accuracy of the network.
