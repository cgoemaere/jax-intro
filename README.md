# Introduction to JAX

This repository provides a short, comprehensive notebook introducing you to [JAX](https://github.com/jax-ml/jax).

## What you'll learn

- **JAX basics**: "It's just NumPy"
- **Functional programming**: How statelessness leads to deterministic randomness and immutable arrays
- **`jit`, `grad`, and `vmap`**: Where the real magic happens
- **Control flow**: Why JAX hates `if-else` and `for`/`while` loops, and what to do about it
- **PyTrees**: You like lists of dicts of tuples of lists? `tree.map` has got you covered!
- **Train a neural network on MNIST**: real AGI with [Equinox](https://github.com/patrick-kidger/equinox)

## Getting started

Grab a fresh cup of coffee and click [here](https://githubtocolab.com/cgoemaere/jax-intro/blob/main/jax_intro.ipynb) to open the notebook in Google Colab!

## Prerequisites

Basic familiarity with Python and NumPy is all you need.

## Why JAX?

Mostly one reason: JAX makes things run *fast*.

Aside from that, JAX makes it a real joy to handle batch dimensions, gradients, and arbitrary datastructures. Trust me, you don't know what you're missing out on here. It's fantastic.

Honestly, just give JAX a try! You can't know that you don't like something if you haven't tried it out. *(triple negation, whoops!)*
