### Object Detection

Fine tuning a deep learning model Yolov8 for object detection

# Real-time Object Detection with YOLOv8

This project implements real-time object detection using a webcam and the YOLOv8 model. It's designed to detect and label objects in a live video stream.

## Features

- Real-time object detection using a webcam
- Utilizes the YOLOv8 model for accurate and fast detection
- Draws bounding boxes and labels around detected objects
- Easy to run and modify

## Requirements

- Python 3.7+
- OpenCV
- Ultralytics YOLOv8
- A webcam

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/harvind-here/Object-Detection.git
   cd Object-Detection
   ```

2. Install the required packages:
   ```
   pip install opencv-python ultralytics
   ```

3. Download the YOLOv8 model:
   The script uses the `yolov8n.pt` model by default. You can download it from the [Ultralytics website](https://github.com/ultralytics/ultralytics) or it will be automatically downloaded when you run the script for the first time.

## Usage

Run the main script:
