## Perceptron - The Simplest Neural Network
# What is a Perceptron?
The perceptron is the basic building block of a neural network. It's a simple computational model that takes several inputs, applies weights to them, adds a bias, and produces an output. It's essentially a decision-making unit.

# Real-life Analogy
Imagine you're trying to decide whether to go outside based on:

Is it sunny?
Is it the weekend?
Are you free today?
You assign importance (weights) to each factor:

Sunny: 0.6
Weekend: 0.3
Free: 0.8
You combine these factors to make a decision: Go or Not Go.

This is what a perceptron does.

# Perceptron Formula
A perceptron takes inputs (x1, x2, ..., xn), multiplies each by its corresponding weight (w1, w2, ..., wn), adds a bias (b), and passes the result through an activation function.

y = f(w1x1 + w2x2 + ... + wn*xn + b)

Where:

xi: input features
wi: weights
b: bias
f: activation function (e.g., step function)

1. A perceptron is the simplest form of a neural network.
2. It performs a weighted sum of inputs, adds a bias, and passes the result through 
3. An activation function to make a decision.
4. It can model simple binary functions like AND, OR, etc.