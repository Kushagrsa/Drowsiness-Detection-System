💤 Drowsiness Detection System

Technologies: YOLOv8, CNN, Computer Vision, Deep Learning

📘 Project Overview

Drowsiness while driving is a major cause of road accidents worldwide. This project implements a real-time driver drowsiness detection system using a combination of YOLOv8 for object detection and Convolutional Neural Networks (CNN) for feature analysis. The system continuously monitors facial expressions, head movement, lane behavior, and steering patterns to detect signs of fatigue before it becomes dangerous.
This solution is designed for real-time performance, making it suitable for deployment in vehicles, driver monitoring systems, and road safety applications.

🎯 Objectives

Detect early signs of driver fatigue with high accuracy
Operate in real-time with minimal latency
Combine multiple detection approaches to reduce false positives
Provide a scalable and reliable computer vision pipeline

🧠 Model Architecture

The system integrates four independent yet complementary models to improve overall detection reliability:

1. Eye & Mouth Detection (CNN)

Analyzes:

Eye openness
Eye blinking frequency
Mouth opening (yawning)
Used to detect visual fatigue cues such as prolonged eye closure or repeated yawns.

2. Steering Behavior Analysis

Monitors:

Abrupt steering corrections
Rapid or inconsistent changes in wheel angle
Erratic steering behavior often correlates with reduced alertness.

3. Lane Detection Model

Identifies:

Unintended lane departure
Drift frequency
Strength of lane-keeping behavior
This helps detect loss of attention or micro-sleep episodes.

4. Head Nodding Detection

Tracks:

Sudden downward head motion
Repetitive micro-nods
Unsteady head positioning
Head nodding is one of the most common signs of driver drowsiness.

⚙️ Technologies & Tools

YOLOv8 – real-time object detection
CNN Models – eye, mouth, and head movement analysis
OpenCV – video capture and preprocessing
NumPy / Python – model integration and logic control
Deep Learning (PyTorch/TensorFlow) – training and evaluation
Computer Vision Techniques – lane detection, motion analysis

🚀 Features

Real-time analysis at high FPS
Multi-model fusion for improved accuracy
Low false-alarm rate due to complementary detection layers
Driver alert system (optional audio/visual warnings)
Flexible pipeline for integrating additional vision modules
Scalable for dashcams, in-car systems, and DVRs

🧪 Performance & Validation

Uses deep learning for reliable feature extraction
YOLOv8 ensures robust face and object detection in varying lighting conditions
Cross-validated across multiple test videos

Multi-module approach reduces false positives dramatically
