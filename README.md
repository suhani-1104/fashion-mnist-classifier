# fashion-mnist-classifier
A deep learning model to classify Fashion MNIST images using TensorFlow/Keras

_________________________________________________________________________________________________

Overview

This project implements a deep learning model to classify images from the Fashion MNIST dataset using TensorFlow and Keras. The dataset contains 70,000 grayscale images of 10 categories of clothing items (t-shirts, shoes, bags, etc.).

The model is trained to achieve high accuracy in classifying clothing items and demonstrates practical applications of image classification using neural networks.

_________________________________________________________________________________________________

Dataset:

Dataset Name: Fashion MNIST

Source: Kaggle/Fashion MNIST

Image Size: 28x28 pixels, grayscale

Number of Classes: 10

Class Labels:

1.T-shirt/top

2.Trouser

3.Pullover

4.Dress

5.Coat

6.Sandal

7.Shirt

8.Sneaker

9.Bag

10.Ankle boot
_________________________________________________________________________________________________
Features

Loads and preprocesses the Fashion MNIST dataset.

Normalizes pixel values for better model performance.

Builds a neural network using Keras Sequential API.

Trains the model with training and validation split.

Evaluates model performance on test data.

Generates predictions and visualizes results with matplotlib.

________________________________________________________________________________________________

Requirements

Python 3.x

TensorFlow 2.x

NumPy

Matplotlib

You can install the required libraries using:

pip install -r requirements.txt
________________________________________________________________________________________________

Usage

Clone the repository:

git clone https://github.com/YourUsername/fashion-mnist-classifier.git


Open the notebook in Google Colab or Jupyter Notebook.

Run the notebook cells to:

Load dataset

Train the model

Evaluate accuracy

Visualize predictions

________________________________________________________________________________________________

Results

Achieved ~90% accuracy on the test set (can vary depending on model architecture and epochs).


<img width="990" height="790" alt="image" src="https://github.com/user-attachments/assets/54ae9f2c-37f6-4614-a147-1d77f2f9b1ec" />
Model correctly classifies various clothing items.

Sample predictions visualized below:
