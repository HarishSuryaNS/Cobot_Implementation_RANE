# 🦾 RANE AI Vision Project

An AI-powered robotic vision system for collaborative robots (Cobots) using the Orbbec Gemini 336L depth camera, Computer Vision, and ROS 2.

## 📌 Project Overview

This project is being developed as part of my internship at **Rane Madras Ltd.** The objective is to develop a vision-guided robotic system capable of detecting industrial components, estimating their 3D position and orientation, generating point clouds, and providing accurate pick coordinates for collaborative robots.

The system combines AI-based object detection with depth sensing to enable precise robotic automation.

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

- Orbbec Gemini 336L Depth Camera
- Dobot Nova 5 Collaborative Robot

---

## 💻 Software

- Ubuntu 24.04 LTS
- ROS 2 Jazzy Jalisco
- Python 3.12
- OpenCV
- Orbbec SDK
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
- AI-based object detection
- Object center localization
- Pixel-to-3D coordinate conversion
- Point cloud generation
- Surface analysis
- Robot coordinate estimation
- Vision-guided pick-and-place

---

## 📅 Current Progress

- ✅ Ubuntu environment setup
- ✅ ROS 2 installation
- ✅ Orbbec Gemini 336L setup
- ✅ Python SDK configured
- ✅ RGB image capture
- ✅ Depth image capture
- ✅ Object detection
- ✅ Object center localization
- ✅ Synchronized two Dobot Nova 5 collaborative robots
- ✅ Successfully implemented pick-and-place operation using synchronized cobots
- 🔄 Point cloud generation
- 🔄 Camera Implementation
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

- **Harish Surya N S**
- **Dhanush Raj**

---

## 📜 License

This project is intended for educational, research, and internship purposes.

---

## 🚧 Project Status

**This repository is under active development. New features, documentation, and improvements will be added as the project progresses.**
