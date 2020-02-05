# Multilayer Perceptron


This repository contains the implementation for a blog post I wrote about [Multilayer Perceptrons](https://giothinks.com/multilayer-perceptron/). This is an attempt to show what an MLP is doing during learning and what's the intuition behind the formulation.

To motivate the problem of going beyond linear classifiers, I'm using a non-linear synthetic dataset, two concentric circles (data generation code is in the notebook).

<p align="center">
<img src="imgs/circles.png">
</p>

The notebook also contains visualizations of the learned units (pre-activation), the learned hidden transformation that makes the dataset linearly separable and finally the learned decision boundary in the original space.

## Visualizations

### Decision Boundary
The final decision boundary of the MLP in the original space.
<p align="center">
<img src="imgs/decision_boundary.png">
</p>

### Learned Transformation

A 3D visualization of the dataset after applying the hidden layer.

<p align="center">
<img src="imgs/projection.png">
</p>

### Learned Units
The three lines correspond to the 3 neurons that were learned. It is visualized before the activations are applied to them.

<p align="center">
<img src="imgs/hidden_classifiers.png">
</p>
