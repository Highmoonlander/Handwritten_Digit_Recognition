# Handwritten Digit Recognition

This project demonstrates a deep learning-based approach for recognizing handwritten digits using the MNIST dataset. The model achieves an impressive **99.88% accuracy** on the test dataset, showcasing the effectiveness of neural networks for image classification tasks.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Key Features](#key-features)
- [Setup and Usage](#setup-and-usage)
- [Results](#results)
- [Future Work](#future-work)

## Overview

Handwritten Digit Recognition is a classic machine learning problem that involves classifying grayscale images of digits (0-9). This project uses TensorFlow and Keras to train and evaluate a neural network capable of achieving near-perfect accuracy on the MNIST dataset.

## Dataset

The project utilizes the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which consists of:
- 60,000 training images.
- 10,000 testing images.

Each image is a 28x28 grayscale image of a single digit (0-9), with pixel values normalized to the range [0, 1].

## Model Architecture

The neural network architecture includes:
- **Input Layer**: 784 neurons (28x28 flattened input).
- **Hidden Layers**:
  - Dense layer with 100 neurons and ReLU activation.
- **Output Layer**: 10 neurons (softmax activation) representing digit classes (0-9).

The model is trained using the Adam optimizer and the sparse categorical cross-entropy loss function.

## Key Features

- Achieved **97.88% accuracy** on the test set.
- Includes regularization (Dropout) to prevent overfitting.
- Optimized for high performance with the Adam optimizer.
- Saves the trained model for reuse.

## Setup and Usage

### Prerequisites
- Python 3.8+
- TensorFlow/Keras
- numpy and matplotlib (for preprocessing and visualization)

### Installation
Clone the repository:
```bash
git clone https://github.com/Highmoonlander/Handwritten_Digit_Recognition.git
cd Handwritten_Digit_Recognition
