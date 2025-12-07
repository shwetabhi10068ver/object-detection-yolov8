# 🎯 Real-Time Object Detection with YOLOv8

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/object-detection-yolov8/blob/main/object_detection.ipynb)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-red)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green)

A powerful yet simple object detection system that leverages YOLOv8 (You Only Look Once version 8) to detect and identify objects in images. This project runs seamlessly in Google Colab with a user-friendly interface.

## 📋 Overview

This project implements a real-time object detection system using the state-of-the-art YOLOv8 model. It provides an intuitive interface where users can either use a pre-loaded demo image or upload their own images for object detection. The system identifies and labels various objects with bounding boxes and confidence scores.

The model can detect **80+ different object categories** from the COCO dataset, making it suitable for various applications including surveillance, image analysis, content moderation, and more.

## ✨ Features

- **🎨 Dual Input Options**: Choose between demo image or upload your own
- **⚡ Fast & Accurate**: Uses YOLOv8-nano for quick yet reliable detection
- **📊 Detailed Results**: Shows object counts, confidence scores, and visual bounding boxes
- **🌐 No Installation Required**: Runs directly in Google Colab with free GPU
- **🎯 80+ Object Classes**: Detects people, vehicles, animals, household items, and more
- **📱 User-Friendly Interface**: Simple menu-driven approach

## 🛠️ Technologies & Tools Used

### **Core Technologies**
- **Python 3.8+**: Primary programming language
- **YOLOv8 (Ultralytics)**: State-of-the-art object detection model
- **OpenCV**: Computer vision library for image processing
- **Google Colab**: Cloud-based Jupyter notebook environment

### **Libraries & Frameworks**
- `ultralytics`: YOLOv8 implementation
- `opencv-python`: Image processing and visualization
- `Pillow`: Image handling
- `numpy`: Numerical operations

### **Platform**
- **Google Colab**: Provides free GPU acceleration
- **GitHub**: Version control and project hosting

## 🚀 Installation & Setup

### **Option 1: Run in Google Colab (Recommended)**
1. Click the "Open in Colab" badge above
2. Sign in with your Google account
3. Click **Runtime** → **Run all** or execute cells sequentially
4. Follow the on-screen menu instructions

### **Option 2: Local Installation**
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/object-detection-yolov8.git
cd object-detection-yolov8

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install ultralytics opencv-python pillow

# Run the notebook (requires Jupyter)
jupyter notebook object_detection.ipynb
