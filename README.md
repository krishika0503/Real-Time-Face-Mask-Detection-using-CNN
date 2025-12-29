# Real-Time-Face-Mask-Detection-using-CNN
Building a real time face mask detection using various coding languages.

This project performs real-time face mask detection using a webcam.

## Features
- Live camera feed
- Face detection using Haar Cascade
- Mask / No Mask detection

## Technologies Used
- Python
- OpenCV
- NumPy

## How to Run
```bash
python live_camera.py

## CNN-Based Mask Detection Model

This project includes a Convolutional Neural Network (CNN) implemented using TensorFlow and Keras.

### CNN Architecture
- Convolutional layers for feature extraction
- Max-pooling layers for dimensionality reduction
- Fully connected layers for classification
- Softmax output layer for Mask / No Mask prediction

### Working Pipeline
1. Face detected using OpenCV
2. Face region resized to 224x224
3. Image passed to CNN model
4. CNN predicts MASK or NO MASK

### Model Execution
The CNN model is defined in `cnn_model.py`.
Training and inference can be performed once the dataset is provided.

### Note
Due to environment constraints, real-time inference is demonstrated using OpenCV logic, while CNN implementation is included as the primary classification model.
