# PRODIGY_ML_04
This project develops a Hand Gesture Recognition Model using Convolutional Neural Networks (CNN) to classify different hand gestures from image data.

Hand Gesture Recognition using CNN
Deep Learning Project | Computer Vision | Human-Computer Interaction

Project Overview
This project develops a Hand Gesture Recognition Model using Convolutional Neural Networks (CNN) to classify different hand gestures from image data.
The model is trained on the LeapGestRecog dataset from Kaggle and can accurately recognize multiple gesture categories, enabling gesture-based control systems and intuitive human-computer interaction.

Dataset Name: LeapGestRecog
Source: Kaggle
Link: https://www.kaggle.com/gti-upm/leapgestrecog

Dataset Description
Contains 20,000+ grayscale images
10 different gesture classes
Images are 240x320 resolution
Organized into folders by subject and gesture

Example gestures:
Palm, L, Fist, Fist moved, Thumb, Index, OK, Palm moved, C, Down

Objective
To build a Deep Learning model that:
Reads hand gesture images
Learns gesture patterns using CNN
Classifies gestures into correct categories
Achieves high validation accuracy
Can be extended for real-time applications

Technologies Used
Python
TensorFlow / Keras
NumPy
OpenCV
Matplotlib
Google Colab

Model Architecture
The CNN model consists of:
Convolution Layers
ReLU Activation
MaxPooling Layers
Dropout Layers
Fully Connected Dense Layers
Softmax Output Layer

Data Preprocessing
Resize images to 64x64
Normalize pixel values
Convert labels to categorical format
Split dataset into training and validation sets

Model Evaluation
Accuracy
Loss curves
Confusion matrix

Results
Training Accuracy: ~95–99%
Validation Accuracy: ~92–97%
Model performs well across gesture classes
