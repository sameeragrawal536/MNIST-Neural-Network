# MNIST-Neural-Network

A multilayer perceptron neural network with 2 hidden layers trained on the MNIST dataset. Achieved 88% accuracy on the test set, trained using gradient descent.

Neural Network Stats:
 - Contains 2 hidden layers
    - Input layer: 784 nodes
    - Hidden layer #1: 32 nodes
    - Hidden layer #2: 10 nodes
    - Output layer: 10 nodes
  
 - Activation Function: Sigmoid Function
 
 - Cost Function: Quadratic Cost Function

 - Learning Rate: 0.01

 - Average training time: 14.15 seconds

The file titled "mnist.txt" is the training data, and the file titled "mnist2.txt" is the test data.

"Neural Network.py" trains the network and saves the weights and biases in 4 text files.

"Neural Network Runner.py" uses the weights and biases given in those files to create a new neural network, so you can use the Network without having to train it.
