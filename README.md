# Waste Image Classification

A deep learning project for classifying waste images into six categories using transfer learning with MobileNetV2.

## Overview

This project develops an image classification model capable of identifying six types of waste:

- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

The project covers the complete machine learning workflow, including image preprocessing, data augmentation, model training, validation, and evaluation.

## Model

The classification model is based on **MobileNetV2** using transfer learning.

The model uses:

- MobileNetV2 as the base model
- Image preprocessing and normalization
- Data augmentation
- A custom classification head
- Early stopping
- Learning-rate reduction
- Model evaluation on a held-out test set

## Technologies

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- MobileNetV2
- Google Colab

## Results

The trained model achieved **93.42% test accuracy** on the six-class waste classification task.

## Prediction Interface

A Gradio-based interface was developed to allow users to upload an image and receive a predicted waste category.

The interface also provides Arabic labels for the predicted categories.

## Project Structure

```text
waste-image-classification/
│
├── Image_Waste_Classification.ipynb
├── README.md
└── .gitignore
