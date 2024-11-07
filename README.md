# Handwritten Digit Recognition

## Overview
This project involves recognizing handwritten digits using a neural network trained on the MNIST dataset. The MNIST dataset contains 70,000 images of handwritten digits, each labeled with the corresponding digit.

## Dataset
The MNIST dataset is a benchmark dataset in the field of machine learning. It includes:
- 60,000 training images
- 10,000 testing images

Each image is a 28x28 pixel grayscale image of a single handwritten digit from 0 to 9.

## Model Architecture
The neural network used in this project consists of the following layers:
1. Input Layer: 28x28 neurons (flattened to 784)
2. Hidden Layer 1: Dense layer with 128 neurons and ReLU activation
3. Hidden Layer 2: Dense layer with 64 neurons and ReLU activation
4. Output Layer: Dense layer with 10 neurons (one for each digit) and softmax activation

## Installation
To run this project, you'll need Python and some additional libraries. You can install the required dependencies using pip:
