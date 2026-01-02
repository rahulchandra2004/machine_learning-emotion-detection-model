# Emotion Detection Model using Machine Learning

# Overview
This project implements a real-time emotion detection system using a Convolutional Neural Network (CNN). It captures facial expressions via webcam, detects faces using OpenCV, and classifies emotions using a pre-trained Keras model. The system is designed for applications in human-computer interaction, affective computing, and smart environments.

# Repository Contents
- `Emotion Detection Model.ipynb`: Main notebook for training and deploying the emotion detection pipeline.
- `emotion_detection_model.h5`: Pre-trained Keras model for emotion classification.
- `README.md`: Project documentation.
- `Emotion Detection Model using machine learn...`: Presentation 

# Model Details
- **Architecture**: CNN trained on grayscale facial images resized to 48x48 pixels.
- **Emotion Classes**: `['Angry', 'Disgust', 'Fear', 'Happy', 'Sad', 'Surprise', 'Neutral']`
- **Libraries Used**: TensorFlow, Keras, OpenCV, NumPy
- **Face Detection**: Haar Cascade Classifier from OpenCV

# Live Emotion Detection (Colab)
The notebook includes a JavaScript-based webcam capture utility for Google Colab:
1. Captures a photo using browser webcam.
2. Detects faces using Haar cascades.
3. Predicts emotion using the loaded `.h5` model.
4. Annotates the image with bounding boxes and predicted labels.

# Installation
```bash
!pip install opencv-python-headless
!pip install tensorflow
