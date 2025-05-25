# Real-Time Face Detection and Tracking

This project uses OpenCV and MediaPipe to perform real-time face detection using your computer's webcam.

## Setup

1. Make sure you have Python 3.x installed on your system
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On macOS/Linux
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Make sure your virtual environment is activated:
   ```bash
   source venv/bin/activate
   ```
2. Run the face detection script:
   ```bash
   python face_detection.py
   ```
3. A window will open showing your webcam feed with face detections
4. Press 'q' to quit the program

## Features

- Real-time face detection using MediaPipe
- Displays confidence scores for each detected face
- Shows bounding boxes around detected faces
- Simple and intuitive interface

## Requirements

- Python 3.x
- Webcam
- Required packages (see requirements.txt):
  - opencv-python
  - numpy
  - mediapipe 