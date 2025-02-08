# Anime Face Generation using DCGAN (Keras & TensorFlow)

## Overview

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) to generate anime-style face images. The model is trained using TensorFlow and Keras on a dataset of anime faces, learning to produce high-quality synthetic images.

## Dataset

The dataset consists of anime face images loaded from the specified directory and preprocessed for training.

## Model Architecture

The DCGAN consists of two neural networks:

Generator: Generates realistic anime faces from random noise.

Discriminator: Distinguishes between real and generated images, providing feedback to improve the generator.

Both networks use Convolutional layers, Batch Normalization, and LeakyReLU activations to improve stability and performance.

## Implementation Details

Framework: TensorFlow & Keras

Training: Adam optimiser, Binary Cross-Entropy loss

Image Preprocessing: Resizing, Normalization

Visualisation: Matplotlib for displaying generated images during training

## Results

The trained model generates high-quality anime faces after sufficient training epochs. Sample outputs are visualised to track the improvement of generated images over time.
