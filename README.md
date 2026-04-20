# Face Detection using OpenCV

## Description
A Python-based face detection system using OpenCV's Haar Cascade Classifier.
Detects human faces in static images and live webcam feed in real-time.

## Technologies Used
- Python 3.x
- OpenCV (cv2)
- Haar Cascade Classifier (haarcascade_frontalface_default.xml)
- Matplotlib

## Features
- Detect faces in any image file
- Real-time face detection using webcam
- Draws bounding boxes with labels around detected faces
- Saves annotated output image

## How to Run
pip install opencv-python matplotlib
jupyter notebook face_detection.ipynb

## How it Works
1. Load image → convert to grayscale
2. Apply Haar Cascade classifier (detectMultiScale)
3. Draw green bounding boxes around detected faces
4. Display and save output
