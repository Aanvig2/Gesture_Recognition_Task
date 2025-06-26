# 👋 Hand Gesture Recognition System

A real-time hand gesture recognition tool using **Google's MediaPipe** and **OpenCV**. This project demonstrates how to use pre-trained MediaPipe models to detect hand landmarks and gestures in live video.
> Note: This project does **not** include any custom model training. It simply integrates Google’s official models and displays output via OpenCV.

---

## Features

### Core Functionality
- Real-time gesture recognition using webcam
- Detects up to **2 hands simultaneously**
- **Handedness detection** (Left/Right)
- Tracks **21 hand landmarks** per hand
- Displays **gesture type** and **confidence scores**

### Visualization
- Live camera feed with hand overlays
- On-screen text showing:
  - Detected gestures
  - Handedness (Left/Right)
  - Confidence levels
  - Landmark positions (normalized and world coordinates)

![image](https://github.com/user-attachments/assets/b8c3dca4-7c41-4bf8-9bdf-76eb231e92c1)
---

## How to Use

### Prerequisites
- Python 3.8+
- A working webcam

### Installation
Install dependencies:
```bash
pip install opencv-python mediapipe numpy
```
