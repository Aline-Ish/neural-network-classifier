# neural-network-classifier
# Simple Neuron Weight Classifier
Final project for the Building AI course

## Summary
This project demonstrates the fundamental math behind a single neuron's output. It calculates weighted sums and applies different activation functions (Identity and Sigmoid) to determine classification probabilities for binary tasks like "Dog vs Cat."
Building AI course project.

## Background
Understanding how weights and activation functions interact is the first step in demystifying deep learning. This project solves the problem of:
* Visualizing how input features (like height/weight) are mathematically processed.
* Demonstrating why specific activation functions are required for classification.
* Providing a clear, step-by-step calculation of neuron outputs.

## How is it used?
This solution is used by students or developers learning the basics of AI. By changing weights and inputs, users can see how the probability of a classification changes.

For example, given inputs (1.3, -2.2, 9.5) and weights (-0.76, 0.22, 0.56), the neuron produces a high probability (~0.98), suggesting a strong classification toward the positive class.

## Data sources and AI methods
The data used in this example comes from the Building AI course exercises.
* **Methods:** Weighted sum calculation ($z = \sum w_i x_i$).
* **Activation Functions:** * Identity Function ($f(x) = x$)
  * Sigmoid Function ($\sigma(z) = 1 / (1 + e^{-z})$)

## Challenges
This project is a simplified model and does not account for:
* Backpropagation or learning (weights are currently static).
* Multiple layers (Hidden layers) which are necessary for complex patterns.
* Large datasets (it currently processes one sample at a time).

## What next?
Next, I would like to expand this into a multi-layer perceptron (MLP) using Python and NumPy to handle larger arrays of data and implement a training loop.

## Acknowledgments
* Building AI Course by Reaktor and University of Helsinki.
