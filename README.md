# ImageCaption_Generator
The Image Caption Generator project creates image descriptions using two models.One  based on VGG16 and another based on ResNet50. Both models help in automatically generating descriptive text for images. 

## Table of Contents
1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Features](#features) 

## Overview

### Model 1: (VGG16)
This model uses the VGG16 architecture, which processes images through several convolutional layers to extract features. It then generates captions based on these features. The VGG16 model is straightforward and effective for image captioning tasks.

### Model 2: (ResNet50)
This model employs the ResNet50 architecture, which includes residual connections to improve learning. It generates captions by understanding image details more accurately, leading to better descriptive text than simpler models.

## Technologies Used
- **Python**: The programming language for the project.
- **TensorFlow/Keras**: Libraries for building and training the neural networks.
- **NumPy**: For numerical operations and array manipulations.
- **PIL**: For image processing tasks.

## Features

### Model 1:
- Generates captions for images.
- Simple architecture that is quick to train.
- Easy to implement and modify.

### Model 2: 
- Produces better captions using advanced techniques.
- Better understanding of image details for more accurate descriptions.
- Generally outperforms the VGG16 model.
