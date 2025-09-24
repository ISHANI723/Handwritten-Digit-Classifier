# Project Title: Handwritten-Digit-Classifier

# Description:
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) using the MNIST dataset. Users can upload images of handwritten digits, and the model predicts the digit in real-time. This project demonstrates the use of deep learning for image classification, including image preprocessing, CNN architecture design, and model training.

# Features: 

1. Train a CNN on the MNIST dataset to recognize handwritten digits.
2. Upload custom images (PNG/JPG) to predict digits.
3. Visualize uploaded images and model predictions.
4. Lightweight model suitable for educational and demonstration purposes.
5. Implemented using Python, TensorFlow/Keras, and Pillow.
6. Fully compatible with Google Colab and local Python environments.

# Dataset:
MNIST Dataset: Contains 70,000 grayscale images of handwritten digits (28x28 pixels). 

# Technologies:
-Python 3.x

-TensorFlow / Keras – Deep Learning

-Pillow (PIL) – Image processing

-NumPy – Array manipulation

-Matplotlib – Image visualization

-Google Colab – Cloud-based Python execution (optional)

# How it Works:

1. Data Preprocessing:

   Convert images to grayscale, normalize pixel values (0-1), reshape for CNN input.

2. CNN Architecture:
   Convolutional layers to extract features
   
   Max-pooling layers to reduce dimensions
   
   Fully connected layers for classification

4. Prediction:
   Upload image → preprocess → CNN predicts → output displayed with the uploaded image.
