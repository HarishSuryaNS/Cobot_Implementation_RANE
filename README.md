# RANE-Project
# 🦾 RANE AI Vision Project

An AI-powered robotic vision system for collaborative robots (Cobots) using Intel RealSense depth cameras, Computer Vision, and ROS 2.

## 📌 Project Overview

This project is being developed as part of my internship at **Rane Madras Ltd.** The objective is to develop a vision-guided robotic system capable of:

- Detecting industrial components
- Estimating object position in 3D space
- Generating point clouds
- Identifying object orientation
- Providing accurate pick coordinates for collaborative robots

The system integrates AI-based object detection with depth sensing for precise robotic automation.

---

## 🎯 Objectives

- Real-time object detection
- 2D to 3D coordinate conversion
- Point cloud generation
- Object pose estimation
- Robot pick-point calculation
- Vision-guided robotic automation

---

## 🛠️ Hardware

- Orbbec Gemini 336L Camera
- Dobot Nova 5 Collaborative Robot

---

## 💻 Software

- Ubuntu 24.04 LTS
- ROS 2 Jazzy Jalisco
- Python 3.12
- OpenCV
- Intel RealSense SDK 2.0
- NumPy
- Open3D
- Ultralytics YOLO

---

## 📂 Repository Structure

```
RANE-AI-Vision/
│
├── data/
├── models/
├── notebooks/
├── src/
│   ├── camera.py
│   ├── detection.py
│   ├── pointcloud.py
│   ├── segmentation.py
│   └── utils.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Features

- RGB image acquisition
- Depth image acquisition
- Object detection using AI
- Object center detection
- Pixel to 3D coordinate conversion
- Point cloud generation
- Surface analysis
- Robot coordinate estimation
- Vision-assisted pick and place

---

## 📅 Current Progress

- ✅ Ubuntu environment setup
- ✅ ROS 2 installation
- ✅ Intel RealSense D456 setup
- ✅ Python SDK configured
- ✅ RGB image capture
- ✅ Depth image capture
- ✅ Object detection
- ✅ Object center localization
- 🔄 Point cloud generation
- 🔄 3D object localization
- 🔄 Robot integration

---

## 📖 Future Work

- Instance segmentation
- Object pose estimation
- Surface normal calculation
- Robot hand-eye calibration
- Automatic grasp planning
- AI-assisted inspection
- Full cobot automation

---

## 👥 Contributors

- Harish Surya N S
- Dhanush Raj

---

## 📜 License

This project is intended for educational, research, and internship purposes.

---
