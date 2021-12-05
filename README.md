
# Handwritten-digit-recognition-MNIST

Handwritten Digit Recognition using Convolutional Neural Networks in Python with Keras

## Introduction

MNIST contains 70,000 images of handwritten digits: 60,000 for training and 10,000 for testing. The images are grayscale, 28x28 pixels, and centered to reduce preprocessing and get started quicker.

Keras is a high-level neural network API focused on user friendliness, fast prototyping, modularity and extensibility. It works with deep learning frameworks like Tensorflow, so we can get right into building and training a neural network without a lot of fuss.

## MNIST dataset:

MNIST is a collection of handwritten digits from 0-9. Image of size 28 X 28

![App Screenshot](https://github.com/sonu275981/Handwritten-digit-recognition-MNIST/blob/32065ccd3fc66e6f32fa3b5bb29cd70f30d5722f/mnist.png?raw=true)

## Description

This is a 6 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I chose to build it with keras API (Tensorflow backend) which is very intuitive.

## Code Requirements

python 3.x with following modules installed

- Numpy
- Seaborn
- Tensorflow
- Keras
- Opencv2

## Accuracy

It achieved 99.92% of accuracy with this CNN trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation.

It achieved 99.12% of accuracy on test set of this CNN model trained on GPU.


