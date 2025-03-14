# Gesture-Volume-Controller# Hand Gesture Volume Control

This project implements a hand-tracking-based volume control system using **OpenCV, MediaPipe, and Pycaw**. The system detects a user's hand and adjusts the system volume based on the distance between the thumb and index finger.

## Features
- Hand tracking using **MediaPipe**.
- Detects the position of thumb and index finger tips.
- Calculates the distance between them to adjust volume.
- Displays real-time FPS and volume percentage.

## Dependencies
Ensure you have the following Python libraries installed:
```sh
pip install opencv-python numpy mediapipe comtypes pycaw
```

## How It Works
1. The script captures video using OpenCV.
2. MediaPipe detects hand landmarks.
3. It calculates the distance between the **thumb tip** and **index finger tip**.
4. The distance is mapped to system volume levels using **Pycaw**.
5. A visual bar represents the current volume level.
6. The volume changes in real-time based on hand gestures.

