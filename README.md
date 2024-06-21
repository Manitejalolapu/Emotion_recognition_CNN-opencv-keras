Dataset Link: https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset


Facial Emotion Detection using OpenCV and Keras
Overview
This project aims to detect and recognize facial emotions in real-time using OpenCV and Keras. The application can identify a range of emotions such as happiness, sadness, surprise, anger, and more, based on facial expressions captured through a webcam.

Features
Real-time Emotion Detection: Utilizes webcam feed to detect and classify facial emotions on-the-fly.
Deep Learning: Implements Convolutional Neural Networks (CNNs) using Keras for accurate emotion recognition.
OpenCV Integration: Employs OpenCV for efficient face detection and image processing.
Pre-trained Model: Uses a pre-trained model for emotion recognition, ensuring high accuracy and reduced training time.

Face Detection: OpenCV's Haar Cascades or DNN-based face detector is used to locate faces in the video frame.
Preprocessing: Detected faces are resized and normalized to match the input requirements of the CNN.
Emotion Prediction: The pre-processed face image is passed through the CNN, which outputs probabilities for each emotion class.
Display Results: The detected face is highlighted, and the predicted emotion is displayed on the video feed.
