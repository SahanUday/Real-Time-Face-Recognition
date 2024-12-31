# Real-Time-Face-Recognition

## Overview

This project is a real-time face recognition system that uses Python, OpenCV, and the `face_recognition` library to detect, identify, and label faces from a live webcam feed or image files. It supports switching between multiple cameras and provides confidence scores for the matches.

---

## Features

- Encode faces from images stored in the `faces` directory.
- Real-time face detection and recognition using webcam input.
- Display labeled faces with confidence percentages.
- Easily switch between available cameras.
- Support for scalable processing by resizing frames for better performance.

---

## File Structure

- `faces/`: Directory containing images of known faces. Use filenames as labels (e.g., `john.jpg` for "John").
- `test_images/`: Directory for storing test input images.
- `results/`: Directory for saving outputs, such as labeled test images.
- `main.ipynb`: Jupyter notebook for testing and running the face recognition script.
- `LICENSE`: MIT License for the project.
- `README.md`: This file.

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/YourUsername/Real-Time-Face-Recognition.git
cd Real-Time-Face-Recognition
