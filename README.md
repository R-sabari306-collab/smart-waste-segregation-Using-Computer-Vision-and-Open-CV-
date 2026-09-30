# smart-waste-segregation-Using-Computer-Vision-and-Open-CV-
AI-powered waste classification using CNN and computer vision, with Raspberry Pi integration plans, a Streamlit analytics dashboard and a 3D digital-twin simulation.

@'
# Smart Waste Segregation System Using CNN and Computer Vision

An AI-powered waste classification project using a Convolutional Neural Network (CNN), OpenCV and a Streamlit dashboard.

## Project Overview

The system classifies waste images into five categories:
- Cardboard
- Glass
- Metal
- Paper
- Plastic

The software includes confidence-based validation, temporal stability, detection-event logging and analytics.

## Main Features

- Five-class CNN-based waste classification
- 224 × 224 × 3 image input
- 70% confidence threshold
- Five-frame temporal stability
- 1.5-second duplicate-event cooldown
- SQLite detection history
- Streamlit analytics dashboard
- 3D digital-twin simulation
- Planned Raspberry Pi camera integration

## Technology Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- SQLite
- Streamlit
- Matplotlib

## System Requirements

- Python 3.12 (for the tested development environment)
- Webcam or compatible camera
- Windows or Linux computer
- Dependencies listed in requirements.txt

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/smart-waste-segregation-cnn.git
cd smart-waste-segregation-cnn
