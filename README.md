# MATLAB-CODE-FOR-2-LAYER-ANN

The implementation is vectorised to perform faster.

nn_params are the randomly initialised parameters (Theta values) for the two layers rolled in a single vector/array.

input parametres input_layer_size is the number of features/input variables to be used

hidden_layer1_size and hidden_layer2_size are the number of neurons in the hidden layer1 and 2

num_labels is the number of output units or classes

X is a matrix of features for training/test class for the corresponding sample

y is a matrix which consists of correct labels for the corresponding feature

lambda is the regularisation parameter


The sigmoid(x) function is used as the activation function which is given by 1/1+ exp(-x)

Sigmoidgradient(x) function calculates the derivative which is given as (sigmoid(x))(1-sigmoid(x))

