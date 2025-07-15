# Variational Autoencoder on MNIST

This project implements a **Variational Autoencoder (VAE)** using TensorFlow and Keras to learn compressed latent representations of handwritten digits from the MNIST dataset. The model is trained to reconstruct images and generate new samples by sampling from the learned latent space.

## Features
- Custom encoder and decoder architecture using fully connected layers  
- KL divergence and reconstruction loss balancing    
- Supports dynamic tuning of KL weight for disentangled latent representation

##  Technologies Used
- Python  
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib

## Results
- Smooth reconstructions and realistic image generations  
- Clear interpolation across digit classes in 2D latent space

##  Dataset
- [MNIST](http://yann.lecun.com/exdb/mnist/) — Handwritten digit images (28x28 grayscale)
