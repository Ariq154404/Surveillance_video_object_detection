# CCTV Object Detection Project Sample

## Overview
This project aims to detect objects in real-time from CCTV footage using PyTorch and OpenCV. It leverages the power of deep learning with a pre-trained Faster R-CNN model from PyTorch's model zoo, making it capable of identifying and localizing multiple objects in each frame of the video.

## Features
- Real-time object detection in CCTV footage
- Utilizes a pre-trained Faster R-CNN model
- Bounding box visualization with object labels

## Prerequisites
- Python 3.x
- PyTorch
- OpenCV
- torchvision

## Installation
To set up the project environment, follow these steps:
   ```bash
   git clone https://github.com/Ariq154404/Surveillance_video_object_detection
   pip install torch torchvision opencv-python
   python object_detection.py --video path/to/your/video.mp4
```
![Object Detection Demo](https://github.com/Ariq154404/Surveillance_video_object_detection/blob/main/sample_vid.gif)
