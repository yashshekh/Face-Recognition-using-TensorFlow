# Face-Recognition-using-TensorFlow
# Description
This project implements a real-time face recognition system using TensorFlow and OpenCV. The system utilizes a pre-trained haarcascade model to identify and recognize faces in real-time. This repository contains all the necessary code, model, and resources to set up and run the face recognition system on your local machine.

# Features
Real-Time Face Detection: Detects faces in real-time using OpenCV's Haar Cascade Classifier.
Face Recognition: Classifies detected faces into predefined categories using a TensorFlow-based deep learning model.
Webcam Integration: Captures live video feed from the webcam for real-time face recognition.
User-Friendly Interface: Displays the recognition results directly on the webcam feed with bounding boxes and labels.

# Getting Started
 Prerequisites
 Python 3.x
 TensorFlow
 OpenCV
 NumPy

# Installation
# 1.Clone the repository:
git clone https://github.com/yashshekh/Face-Recognition-using-TensorFlow.git
cd Tensorflow-Face-Recognition

# 2.Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  
On Windows: venv\Scripts\activate

# 3.Download and place the necessary models and resources:
Place the haarcascade_frontalface_default.xml file in the root directory.
Ensure the keras_model.h5 file is in the root directory.

# 4.Running the Project
Activate the virtual environment (if not already activated):
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 5.Run the face recognition script:
python test.py
Press q to exit the webcam feed.

