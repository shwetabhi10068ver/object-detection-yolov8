# 🎯 Object Detection with YOLOv8

A simple yet powerful object detection system using YOLOv8 that runs directly in Google Colab. Detect objects in images with just a few clicks!

![Object Detection Example](https://ultralytics.com/images/bus.jpg)

## ✨ Features

- **Simple Interface**: Only 2 options - use demo image or upload your own
- **Fast & Accurate**: Uses YOLOv8-nano model for quick detection
- **Real-time Results**: See bounding boxes and confidence scores
- **No Setup Required**: Runs directly in Google Colab
- **Free GPU**: Leverages Google Colab's free GPU resources

## 🚀 Quick Start

### Option 1: Run in Google Colab (Recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/object-detection-yolov8/blob/main/object_detection.ipynb)

1. Click the "Open in Colab" button above
2. Sign in with your Google account
3. Click "Runtime" → "Run all" or run cells individually
4. Choose an option from the menu:
   - **Option 1**: Use demo image (automatically downloads a sample)
   - **Option 2**: Upload your own image

### Option 2: Clone and Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/object-detection-yolov8.git
cd object-detection-yolov8

# Install dependencies
pip install ultralytics opencv-python pillow

# Run the script (note: some features require Google Colab environment)
python object_detection.py
