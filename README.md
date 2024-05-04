# Multi-Layer-Perceptron
Create code to make and train an n-layer neural network from scratch
## Part I
Using the XOR gate truth table as the training set for the 2-layer-3-neuron network. Please use
the notation in the lectures slides (“L-layer-NN”) to implement this neural network.

The class NeuralNetwork should have five methods:
* __init__(self, layers, activation=‘sigmoid’):
* fit(self, X, y, learning_rate=0.2, steps=100000, tol=
1e-2):
* find_RMS_error(self, X, y):
* predict(self, x):
* visual_NN_boundaries(self, Nsamp=2000):

### Reporting Training Progress
For Every 1/10 of the specified number of training steps, check the RMS error by applying the
neural net to the training data, and print.

### Learning Metric
Show the smoothed loss function vs. training steps.

### Class Boundaries
Finally, apply the trained neural network to 2000 test data points. Let’s call the ith data point x;
x[0] and x[1] should be between [0, 1] for all values of i. Use the results to visualize the
boundary

## Part II:
Now use this training set:

X = np.array([[0, 0],
[0, 1],
[0.5, 1],
[0, 0.5],
[1, 0],
[1, 1]])

y = np.array([0, 0, 0, 1, 1, 1])

* You may consider increase the complexity of your architecture, e.g., to [2,2,2,1].
* Apply your trained neural net to 2000 test data points (all coordinates should be between 0 and 1) to visualize the boundary.

