# Railway Track Crack Detection Using Deep Learning

A deep learning-based computer vision system for automated railway track crack detection and segmentation. This project presents a comparative study of object detection and segmentation models for identifying defects in railway track images.

## 📌 Project Overview

Railway track inspection is traditionally performed through manual inspection and specialized monitoring systems. This project explores computer vision and deep learning as an automated approach for detecting railway track cracks.

Multiple deep learning architectures were implemented and evaluated, including:

- YOLOv5
- YOLOv8
- U-Net
- MobileNetV2
- ResNet50

The primary focus was on comparing object detection and image segmentation approaches for railway crack analysis.

---

## 🎯 Objectives

- Develop an automated railway track crack detection system.
- Prepare and preprocess railway track image datasets.
- Train object detection models using YOLOv5 and YOLOv8.
- Perform pixel-level crack segmentation using U-Net.
- Compare different deep learning architectures.
- Evaluate models using standard computer vision metrics.
- Explore preprocessing and augmentation techniques for improved detection under varying image conditions.

---

## 🗂️ Dataset

The dataset was prepared using railway track images collected from multiple sources, including publicly available datasets.

The data preparation pipeline included:

1. Dataset collection
2. Data cleaning
3. Image preprocessing
4. Annotation and bounding-box preparation
5. Dataset balancing
6. Image augmentation
7. Training, validation and testing

The final dataset contained both defective/cracked and non-defective railway track images.

---

## 🔬 Methodology

The overall workflow followed the pipeline:

```text
Dataset Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Dataset Balancing
        ↓
Annotation
        ↓
Data Augmentation
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Comparative Analysis
## 🤖 Models Used

### YOLOv5

YOLOv5 was trained for railway crack detection using bounding-box annotations.

### YOLOv8

YOLOv8 was trained using the Ultralytics framework for railway track crack detection.

### U-Net

U-Net was implemented for pixel-level segmentation of railway track crack regions.

### MobileNetV2

MobileNetV2 was considered as a lightweight deep learning architecture for comparative analysis.

### ResNet50

ResNet50 was considered as a deeper CNN architecture for comparative analysis.

---

## 📊 Evaluation Metrics

### Object Detection

- Precision
- Recall
- F1 Score
- mAP@50
- mAP@50–95

### Image Segmentation

- Intersection over Union (IoU)
- Dice Score

---

## 📈 Results

### YOLO Detection Results

One of the evaluated YOLO model runs achieved approximately:

| Metric | Result |
|---|---:|
| Precision | 61% |
| Recall | 44% |
| F1 Score | ~50–52% |
| mAP@50 | 41% |
| mAP@50–95 | 14% |

### U-Net Segmentation Results

The U-Net model achieved:

| Metric | Result |
|---|---:|
| Average IoU | 0.8173 |
| Average Dice Score | 0.8753 |

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Ultralytics YOLO
- OpenCV
- NumPy
- Matplotlib
- Roboflow
- Google Colab

---

## 📁 Repository Structure

```text
railway-track-crack-detection/
│
├── README.md
├── YOLOV5.ipynb
├── YOLOV8_FINAL.ipynb
└── UNET_FINAL.ipynb
