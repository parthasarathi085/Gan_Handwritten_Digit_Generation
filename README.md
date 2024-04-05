# Generative Adversarial Network (GAN) for Handwritten Digit Generation

This repository includes an implementation of a Generative Adversarial Network (GAN) that creates handwritten numbers that resemble those from the MNIST dataset using TensorFlow and Keras.


# Overview

A type of machine learning models called Generative Adversarial Networks (GANs) is intended to produce new data instances that bear similarities to a given dataset. In this project, we create realistic-looking handwritten numbers by using a GAN architecture.

The following are included in the project: - A training script ({gan_mnist.py}) that uses the MNIST dataset to train the GAN model.
- TensorFlow and Keras are used to implement the generator and discriminator models.
- The generated photos that were kept in the training directory, `gen_images`.
- A script for visualisation that shows the generated images.

# Dependencies

- TensorFlow - Keras - NumPy - Matplotlib - Python 3.x

Use pip to install the dependencies:

pip install matplotlib, numpy, keras, and tensorflow

# Application

1. Make a repository clone:

git clone https://github.com/your-username/gan-mnist.git
cd gan-mnist

2. Get the GAN model ready:

Python gan_mnist.py

3. The generated photos will be stored in the `gen_images` directory after the training is finished.

4. Execute the visualisation script to see the created images:

visualize_generated_images.py in Python

# Outcomes
The generated images are visible in the {gen_images} directory upon training. A grid of created photographs will also be displayed by the visualisation script.
