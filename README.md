# Autoencoders with PyTorch

## Overview

This project demonstrates the implementation of two types of autoencoders using PyTorch:

- **Feedforward Neural Network Autoencoder**
- **CNN-based Autoencoder**

Both models are trained on the **FashionMNIST** dataset to learn compressed representations of input images and reconstruct them effectively.

## What are Autoencoders?

Autoencoders are a type of neural network used for **unsupervised learning** of data representations. They are used to learn compact representations of data. Autoencoders consist of two components:

- **Encoder:** Compresses the input into a lower-dimensional latent space.
- **Decoder:** Reconstructs the original input from this latent representation.

Autoencoders are widely used in:
- **Image compression**
- **Denoising**
- **Anomaly detection**

## Dataset

The **FashionMNIST** dataset is a collection of grayscale images (**28x28 pixels**) representing different fashion items such as **shirts, dresses, and shoes**. It contains:
- **60,000** training images
- **10,000** test images

## Implementation Details

- **Feedforward Autoencoder:** A simple neural network with fully connected layers.
- **CNN Autoencoder:** Uses convolutional and deconvolutional layers for improved feature extraction and reconstruction.
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam
- **Training:** Models are trained using PyTorch with the FashionMNIST dataset.

## How to Run

1. **Clone this repository:**
   ```sh
   git clone https://github.com/your-repo/autoencoders-pytorch.git
   cd autoencoders-pytorch
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```

## Results

The trained autoencoders reconstruct images from the FashionMNIST dataset with varying levels of accuracy, depending on the architecture:
- **CNN-based autoencoder** typically achieves better reconstruction quality compared to the feedforward autoencoder.

## Future Improvements

- Experiment with different architectures such as **Variational Autoencoders (VAEs)**.
- Train on more complex datasets.
- Apply autoencoders for **denoising tasks**.

## Author

Dhruv Pharasi
