# YOLOv8 Object Detection Coursework

This repository contains my coursework on object detection with YOLOv8.  
It covers both using a pretrained model for inference and training a model on a custom dataset.

## Technologies

- Python
- Ultralytics YOLOv8
- OpenCV
- Pillow

## Pretrained Model

In this part I:

- ran object detection on images
- experimented with different confidence thresholds
- tested the effect of IOU (NMS)
- filtered detections by class
- applied the model to video and checked FPS

## Custom Training

For the training task I:

- prepared a dataset in YOLO format
- created a YAML configuration file
- used transfer learning with `yolov8n.pt`
- monitored training metrics (loss, mAP)
- evaluated the model on unseen images
