# Fashion-MNIST Convolutional Autoencoder Tutorial

This repository contains the Google Colab notebook and tutorial PDF for a Machine Learning assignment focused on Convolutional Autoencoders (CAE) and Convolutional Denoising Autoencoders (CDAE). The tutorial demonstrates how autoencoders learn compressed representations of images and how denoising techniques improve robustness by reconstructing clean outputs from noisy inputs.

## Contents
- **Autoencoder Tutorial PDF** – A structured tutorial (<2000 words) explaining the theory, architecture, methodology, results and conclusions.
- **Google Colab Notebook (.ipynb)** – Complete, runnable code for training and evaluating CAE and CDAE models, including all figures shown in the tutorial.
- **Figures generated automatically** within the notebook:  
  - Training and validation loss curves  
  - CAE reconstructions  
  - Noisy vs denoised comparisons  
  - Latent-space PCA projection  
  - Reconstruction-error distributions  

## How to Use
1. Open the notebook in Google Colab.  
2. Run each cell in order to reproduce all results and visualisations.  
3. The Fashion-MNIST dataset loads automatically using the Keras API.  
4. All models, plots and analysis in the PDF are generated from this notebook.

## Technique Summary
- **Convolutional Autoencoder (CAE):** Learns low-dimensional latent features and reconstructs images.
- **Convolutional Denoising Autoencoder (CDAE):** Trains on noisy–clean image pairs using a noise factor of 0.4 to learn robust denoising.
- Loss function: Mean Squared Error (MSE)  
- Optimiser: Adam  
- Training: 20 epochs for each model

## Accessibility
All figures use clear colouring, labelling and contrast to support accessibility for readers.

## Dataset
Fashion-MNIST (Keras API): 70,000 grisacle 28×28 clothing images across 10 classes.

## Licence
MIT License.
