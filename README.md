# Object Detection with YOLOv5 & Faster R-CNN

## 📌 Overview

This project implements an object detection system using YOLOv5 and Faster R-CNN, trained on a custom dataset extracted from drone images. The system is designed to detect objects in aerial imagery using PyTorch, OpenCV, and torchvision models.

## 🚀 Features

- Supports YOLOv5 and Faster R-CNN models for object detection.
- Processes drone images with bounding box annotations.
- Uses a custom dataset with extracted text, images, and tables.
- Implements data augmentation and preprocessing.
- Includes custom collate functions for handling variable bounding boxes.
- Trains models using PyTorch DataLoader with efficient batching.
- Evaluates performance using Intersection over Union (IoU) and mAP metrics.
- Provides visualization of detections.

## 📂 Dataset

- The dataset consists of drone images with bounding box annotations.
- **Annotations Format:** `frame_number, object_id, x, y, w, h, class, species, occlusion, noise, image_path`.
- Annotations are loaded from CSV files and converted into a structured dataset.

