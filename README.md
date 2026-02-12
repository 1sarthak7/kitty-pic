

<p align="center">
  <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="220" />
</p>

<p align="center">
  <b>Kitty Face Detection</b>
</p>

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv" />
  <img src="https://img.shields.io/badge/MediaPipe-FaceMesh-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-purple?style=for-the-badge" />
</p>

---

## Project Overview

This project implements a real-time Face Mesh detection system using MediaPipe and OpenCV. The application captures live webcam input, detects facial landmarks, and overlays 468 mesh points with high accuracy and low latency.

Designed for performance and clarity, this project demonstrates practical computer vision implementation optimized for Apple Silicon and modern Python environments.

---

## Key Features

* Real-time webcam processing
* 468 facial landmark tracking
* Smooth frame rendering
* Lightweight architecture
* Apple Silicon optimized setup
* Clean modular code structure

---

## Live Demo Preview

<p align="center">
  <img src="https://media.giphy.com/media/3oriO0OEd9QIDdllqo/giphy.gif" width="500" />
</p>

The application opens a webcam window and overlays dynamic facial mesh points in real time.

---

## System Architecture

```
Webcam Input
      ↓
OpenCV Frame Capture
      ↓
RGB Conversion
      ↓
MediaPipe FaceMesh Processing
      ↓
Landmark Detection (468 points)
      ↓
Overlay Rendering
      ↓
Display Output Window
```

### Flow Explanation

1. OpenCV captures frames from the webcam.
2. Frames are converted from BGR to RGB.
3. MediaPipe FaceMesh processes the image.
4. Facial landmarks are extracted.
5. Landmarks are drawn using OpenCV utilities.
6. Processed frames are displayed in real time.

---

## Installation Guide

### 1. Clone Repository

```
git clone [https://github.com/1sarthak7/kitty-pic] 
```

### 2. Create Virtual Environment (Recommended)

```
python3.11 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```
pip install -r requirements.txt
```

Or manually:

```
pip install opencv-python==4.9.0.80 mediapipe==0.10.14 numpy==1.26.4 Pillow
```

---

## Run the Application

```
python main.py
```

Press Q to exit the webcam window.

---

## Performance Notes (Apple Silicon Recommended Setup)

For stable execution on M-series Macs:

* Python 3.11
* MediaPipe 0.10.14
* OpenCV 4.9
* NumPy 1.26

Avoid Python 3.13+ for legacy MediaPipe API compatibility.

---


## Author

<p align="center">
  <img src="https://media.giphy.com/media/VbnUQpnihPSIgIXuZv/giphy.gif" width="180" />
</p>

**Sarthak Bhopale**
* Engineering Student
* GitHub: [https://github.com/1sarthak7](https://github.com/1sarthak7)

---

** If you found this project useful, consider giving it a star on GitHub. **
