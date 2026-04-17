# Chest X-Ray Pneumonia Detection
This project uses deep learning to classify chest X-ray images as **Normal** or **Pneumonia**. 
A convolutional neural network was trained on a labeled chest X-ray dataset to learn patterns that distinguish healthy lungs from pneumonia interactions.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Features
- Loads and preprocesses chest X-ray image datasets
- Uses data normalization and resizing for model training
- Trains a convolutional neural network for image classification
- Evaluates model performance on validation and test datasets
- Displays training and validation accuracy and loss graphs
- Generates predictions for sample chest X-ray images

## How It Works
1. Chest X-ray images are loaded from a structured dataset.
2. Images are resized and normalized for model training.
3. A convolutional neural network is built using TensorFlow / Keras.
4. The model is trained on labeled training images.
5. Model performace is evaluated using validation and test datasets.
6. The trained model predicts whether new X-ray images show signs of pneumonia.

## Project Purpose
This project was developed to explore how deep learning can be applied to medical image classification tasks. It demonstrates how convolutional neural networks can be trained to identify patterns in medical imaging data. 

## Dataset
This project uses a chest X-ray dataset containing labeled images of **normal lungs** and **pneumonia cases**.
