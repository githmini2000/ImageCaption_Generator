# ImageCaption_Generator
The Image Caption Generator project have developed and evaluated two deep-learning models for generating captions from images as part of my Deep Learning module. The models used are based on VGG16 with LSTM and ResNet50 with a Transformer architecture. This work explores different methods for automatic image description.

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Features](#features)
5. [Preprocessing Steps](#preprocessing-steps)
6. [Performance Evaluation](#performance-evaluation)

## Overview

### Model 1: (VGG16)
This model uses the VGG16 architecture for image feature extraction, combined with an LSTM network to generate captions. It was trained on a dataset of 8,091 images, each paired with human-generated captions. This model demonstrated strong performance in generating accurate captions.

### Model 2: (ResNet50)
This model employs the ResNet50 architecture for feature extraction, enhanced by a Transformer for caption generation. While innovative, this model did not perform as well as the VGG16-LSTM combination in terms of accuracy.

## Dataset
The models were trained on a dataset containing 8,091 images, each paired with corresponding human-generated captions. This dataset allows for comprehensive training and evaluation of the models.

## Technologies Used
- **Python**: The programming language for the project.
- **TensorFlow/Keras**: Libraries for building and training the neural networks.
- **NumPy**: For numerical operations and array manipulations.
- **PIL**: For image processing tasks.

## Features

### Model 1:
- Generates accurate captions for images.
- Simple architecture that is quick to train.
- Effective for automatic image description.

### Model 2: 
- Innovative approach using a Transformer for caption generation.
- Focuses on understanding image details but has lower accuracy compared to VGG16-LSTM.

## Preprocessing Steps
Key preprocessing steps included:
- Resizing images to a uniform size.
- Normalizing pixel values for better model performance.
- Tokenizing captions to prepare them for training.

## Performance Evaluation
Model performance was assessed using BLEU scores, which measure the accuracy of generated captions. The VGG16-LSTM model outperformed the ResNet50-Transformer in generating more accurate captions.
