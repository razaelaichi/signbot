# SignBot

### A Minimal Neural Network Built From Scratch

**By Raza Abbas R H Rizvi — 2026**

## Overview

SignBot is a minimal binary classification project built to predict whether a number is positive or negative using a neural network created from scratch in PyTorch.

The goal of this project was not complexity, but understanding. Instead of relying on high-level abstractions, I focused on learning how neural networks actually work at the mathematical and computational level.

This project became my introduction to:

* forward propagation
* weight initialization
* loss computation
* gradient-based learning
* parameter optimization
* binary classification

---

## Project Objective

The neural network receives a numerical input and learns to classify it into one of two categories:

* Positive Number → `1`
* Negative Number → `0`

What makes this interesting is that the model was never explicitly programmed with comparison operators or rules like:

```python id="1lhgci"
if x > 0
```

Instead, it learned the decision boundary entirely through training.

---

## What I Learned

### Understanding Neural Networks Fundamentally

This project helped me stop treating machine learning as a black box.

I learned how inputs move through a network, how predictions are generated mathematically, and how parameters gradually improve during training.

---

### Learning Through Randomness

One of the most fascinating parts of the project was watching randomly initialized weights evolve into meaningful parameters.

The model began with no understanding of positive or negative numbers, yet through repeated optimization it learned to separate them correctly with high accuracy.

---

### Forward Pass and Prediction Logic

I implemented and understood:

* weighted sums
* activations
* prediction generation
* probability interpretation

The core prediction equation used was:

$\hat{y}$= $\sigma$(wx+b)

This simple equation became the foundation for understanding how larger neural networks operate.

---

### Loss and Optimization

I learned how models measure error using loss functions and how gradient descent updates parameters to reduce that error over time.

This was the point where machine learning started feeling logical instead of magical.

---

### Emergent Decision Boundaries

The most mind-blowing realization was seeing a single neuron independently learn that zero acts as a separating boundary between positive and negative numbers.

That behavior emerged naturally from training data without hardcoded logic.

---

## Technologies Used

* Python
* PyTorch
* Pandas

---

## Key Takeaway

Although SignBot is a very small project, it gave me a foundational understanding of how neural networks learn.

Building something minimal from scratch provided more insight than using large prebuilt frameworks without understanding the internals.

This project became the starting point for exploring:

* language models
* embeddings
* multi-layer neural networks
* character-level prediction systems
* deep learning architectures

Thanks for reading, have a nice day <3
