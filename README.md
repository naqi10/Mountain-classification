
# Mountain-classification

This repository contains a Flask-based web application that classifies images into six categories: buildings, forest, glacier, mountain, sea, and street. The classification model is built using TensorFlow and Keras and is trained to distinguish between different types of landscapes.

Features
Deep Learning Model: Uses a pre-trained Keras model for multi-class image classification.
Web Interface: Built with Flask to allow users to upload images and receive classification results.
Image Preprocessing: Resizes and normalizes images before feeding them into the model.
Confidence Filtering: Ensures reliable predictions by applying a confidence threshold.
How It Works
The user uploads an image through the web interface.
The application preprocesses the image (resizing, normalization).
The model makes a prediction and returns the most likely class.
If the confidence level is below 50%, the image is classified as "not a recognizable category."
