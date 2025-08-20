# YOLOv8-ObjectDetection-DL

## Overview

This project implements **YOLOv8** for object detection as part of the course
**DVA307 – Deep Learning and Neural Networks** at Mälardalen University (2025).
The focus is on understanding object detection frameworks, training YOLOv8,
and evaluating performance on image data.

---

## Objectives

* Learn the YOLO object detection pipeline
* Train and evaluate YOLOv8 using Ultralytics/PyTorch
* Explore the YOLOv8 loss function and evaluation metrics
* Analyze model performance and detection trade-offs

---

## Tech Stack

* Python
* PyTorch
* Ultralytics YOLOv8
* Jupyter Notebook

---

## Repository Structure

```
MDU_Lab3_Yolo.ipynb   # Notebook with training and evaluation
README.md             # Documentation
```

---

## Key Learnings

* **Loss function:** YOLOv8 combines IoU-based bounding box regression,
  binary cross-entropy for classification, and objectness loss
* **Anchor-free detection:** predicts bounding boxes directly at feature map
  locations (no predefined anchors)
* **Data augmentation:** mosaic, flipping, scaling, and color jitter applied
  automatically during training
* **Evaluation metrics:** mAP\@50, mAP@\[50:95], precision, and recall
* **Post-processing:** confidence thresholds and Non-Maximum Suppression (NMS)
  control which detections are kept
* **Trade-offs:** larger input sizes improve accuracy but reduce inference speed

---

## Course Context

* **Course:** DVA307 – Deep Learning and Neural Networks
* **Assignment 3:** Object Detection with YOLOv8
* **Institution:** Mälardalen University, 2025

---


