# Handwritten Digit Recognition with CNN
# Overview

This project implements a Handwritten Digit Recognition system using Convolutional Neural Networks (CNNs) trained on the MNIST dataset. The model classifies digits (0-9) from handwritten images with high accuracy.
# Dataset
1.MNIST Dataset: A collection of 60,000 training images and 10,000 testing images of handwritten digits (28x28 pixels, grayscale).

2.The dataset is available in TensorFlow/Keras datasets.
# Model Architecture

The model consists of:

1.Conv2D Layers: Extract spatial features from images.

2.MaxPooling2D: Reduces feature map dimensions.

3.Flatten: Converts features into a single vector.

4.Dense Layers: Fully connected layers for classification.

5.Dropout: Prevents overfitting.
# Training Performance

1. Train Accuracy: ~99.07%

2. Validation Accuracy: ~99.11%

3. Test Accuracy: ~98.81%
