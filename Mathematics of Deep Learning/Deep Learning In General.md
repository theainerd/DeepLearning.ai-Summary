## Deep Learning

Deep learning is a particular kind of machine learning that achieves great power and flexibility by learning to
represent the world as a nested hierarchy of concepts, with each concept defined in
relation to simpler concepts, and more abstract representations computed in terms
of less abstract ones.

## Cost Functions

### Cross-entropy

A generalization of Log Loss to multi-class classification problems. Cross-entropy quantifies the difference between two probability distributions.

## Activation Function

A function (for example, ReLU or sigmoid) that takes in the weighted sum of all of the inputs from the previous layer and then generates and passes an output value (typically nonlinear) to the next layer.

## BackPropagation

The primary algorithm for performing gradient descent on neural networks. First, the output values of each node are calculated (and cached) in a forward pass. Then, the partial derivative of the error with respect to each parameter is calculated in a backward pass through the graph.

## Batch

The set of examples used in one iteration (that is, one gradient update) of model training.

## Epoch

A full training pass over the entire data set such that each example has been seen once. Thus, an epoch represents N/batch size training iterations, where N is the total number of examples.

## Bias (Math)

An intercept or offset from an origin. Bias (also known as the bias term) is referred to as b or w0 in machine learning models. For example, bias is the b in the following formula:

Not to be confused with bias in ethics and fairness or prediction bias.

## Dropout regularization

A form of regularization useful in training neural networks. Dropout regularization works by removing a random selection of a fixed number of the units in a network layer for a single gradient step. The more units dropped out, the stronger the regularization. This is analogous to training the network to emulate an exponentially large ensemble of smaller networks. For full details, see Dropout: A Simple Way to Prevent Neural Networks from Overfitting.

## Early stopping

A method for regularization that involves ending model training before training loss finishes decreasing. In early stopping, you end model training when the loss on a validation data set starts to increase, that is, when generalization performance worsens.

## Softmax

A function that provides probabilities for each possible class in a multi-class classification model. The probabilities add up to exactly 1.0. For example, softmax might determine that the probability of a particular image being a dog at 0.9, a cat at 0.08, and a horse at 0.02. (Also called full softmax.)

