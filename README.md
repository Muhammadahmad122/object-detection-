# Object Detection with OpenCV and TensorFlow

## Overview
This project implements object detection using OpenCV and TensorFlow. It processes traffic videos to count objects (e.g., vehicles) passing through a road, while also calculating important metrics like IoU (Intersection over Union), precision, recall, and more.

## Features
- Detects and counts objects in traffic videos
- Outputs object detection metrics (e.g., IoU, precision, recall)
- Customizable for different object detection tasks

## Requirements
To install the required dependencies, simply run:
```bash
pip install -r requirements.txt
```

## How to Use 
- Clone the Repository:
```bash
  git clone https://github.com/Muhammadahmad122/object-detection-
```
- Navigate to the Project Directory:
```bash
  cd your-repository-name
```
- Run the Object Detection Script:
```bash
  python object_detection.py
```
- Input Video: The script processes the input video and counts objects in real-time. You can modify the source to handle other types of input, including live camera feeds or different video formats.
## Example Output
-Objects counted: 15
-IoU: 0.85
-Precision: 0.90
-Recall: 0.88
