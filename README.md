# CNN on MNIST (LeNet and AlexNet)

This project implements two classic convolutional neural network architectures, LeNet and AlexNet, and trains them on the MNIST handwritten-digit dataset. It started as a deep-learning study project for the Information Systems course at UFMS, and the goal was to build these foundational CNNs from scratch and compare how they behave on the same task.

## Why these two architectures

LeNet and AlexNet are two of the architectures that shaped modern computer vision. LeNet is the small, early design that proved CNNs could read digits reliably. AlexNet came later and is much deeper and wider, the network that brought CNNs back into the spotlight. Putting both on MNIST is a good way to see the difference between a compact model built for digit recognition and a heavier model originally meant for far larger images, here adapted down to the MNIST setting.

## What's in the repo

There are two notebooks, one per architecture:

- `CNN_para_MNIST_LeNet.ipynb`, the LeNet-style network.
- `CNN_para_MNIST_AlexNet.ipynb`, an AlexNet-style network adapted to MNIST.

Each notebook walks through loading the data, building the model, training it, and evaluating it on the digit classification task.

## Tech stack

Python with TensorFlow and Keras for the models, and the standard MNIST dataset for training and evaluation.

## How to run

Open either notebook in Jupyter (or Google Colab) and run the cells top to bottom. The MNIST dataset is loaded directly through Keras, so there is nothing to download by hand. Start with the LeNet notebook if you want the simpler model first, then move to AlexNet to compare.

---

Part of [@gwillye](https://github.com/gwillye)'s portfolio. Author: Gabriel Willye.
