# Variational Autoencoder on Fashion-MNIST

This repository contains an implementation of a **Variational Autoencoder (VAE)** trained on the Fashion-MNIST dataset to learn compact latent representations and generate new samples.

## Overview
A VAE is a generative model that encodes input data into a probabilistic latent space and decodes samples back to the input domain. This project focuses on understanding:
- Latent representation learning
- The reparameterization trick
- Trade-offs between reconstruction quality and latent regularization

## Key Features
- Encoder–decoder architecture implemented in PyTorch
- Latent space modeled using mean and log-variance
- Reparameterization trick for backpropagation through stochastic nodes
- Optimization using **Binary Cross-Entropy + KL divergence**
- **β-VAE experiments** (β = 0.1, 0.5, 1) to study disentanglement vs reconstruction quality

## Experiments & Analysis
- Latent space visualization across different β values
- Reconstruction comparison between original and decoded images
- Sampling from latent space to evaluate generative diversity

