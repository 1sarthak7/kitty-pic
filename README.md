<div align="center">

# Real-Time Face Mesh Detection

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Face%20Mesh-00A99D?style=for-the-badge&logo=google&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

<br />

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmZ5Z3J5aW55Z3J5aW55Z3J5aW55Z3J5aW55Z3J5aW55Z3J5aSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o7TKSjRrfIPjeiVyM/giphy.gif" alt="Face Mesh Demo Animation" width="600">

<br />

**A high-performance computer vision application that maps 468 distinct facial landmarks in real-time.**

<br />

[View Demo](#) · [Report Bug](#) · [Request Feature](#)

</div>

<br />

<div align="center">

## About The Project

This project leverages the power of Google's MediaPipe framework alongside OpenCV to create a robust facial landmark detection system. Unlike traditional bounding-box face detection, this application generates a dense mesh of 468 3D data points, allowing for precise tracking of facial geometry, expressions, and orientation.

The system captures live video feed from a standard webcam, processes the frames using the MediaPipe Face Mesh solution, and renders the triangulation overlay onto the video feed with low latency. This technology is foundational for applications involving augmented reality filters, avatar animation, and drowsiness detection systems.

</div>

<div align="center">

## Key Features

**High-Fidelity Tracking**
Detects and tracks 468 3D facial landmarks with sub-millimeter precision.

**Cross-Platform Compatibility**
Optimized to run smoothly on macOS (Apple Silicon), Windows, and Linux environments.

**Real-Time Performance**
Utilizes efficient pipeline architecture to maintain high FPS during live video processing.

**Visual Customization**
Includes options to adjust the thickness, color, and radius of the mesh connections and landmarks.

</div>

<div align="center">

## Technologies Used

![Python](https://img.shields.io/badge/Python-FFD43B?style=flat&logo=python&logoColor=blue)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-00A99D?style=flat&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

</div>

<div align="center">

## Installation

Follow these steps to set up the environment and run the application locally.

**1. Clone the Repository**
```bash
git clone [https://github.com/your-username/face-mesh-detection.git](https://github.com/your-username/face-mesh-detection.git)
