

---

# **UNDERWATER-OBJECT-DETECTION-USING-YOLO**

## Overview
**UNDERWATER-OBJECT-DETECTION-USING-YOLO** is a project aimed at detecting and classifying underwater trash using the YOLO (You Only Look Once) object detection algorithm. This system focuses on distinguishing between biodegradable and non-biodegradable waste to aid in underwater cleanup efforts. Leveraging advanced versions of YOLO, including YOLOv4, YOLOv5, YOLOv7, YOLOv8, and the latest YOLOv9, the project achieves high accuracy in identifying various types of underwater debris.

This project uses custom datasets as well as open-source data from JAMSTEC to train the models and refine the detection system, ultimately providing an effective solution for underwater trash categorization.

## Key Features
- **Trash Detection**: Detects underwater trash and classifies it as biodegradable or non-biodegradable.
- **YOLOv9 Performance**: Achieved a mean average precision (mAP) of 90.3% with YOLOv9 after training on an augmented dataset.
- **Dataset Expansion**: Initial dataset of 155 images expanded to 1180 images using professional cameras and the JAMSTEC Underwater Plastic Dataset.
- **Model Training**: Fine-tuned YOLO models with batch size 24 and 120 epochs, achieving optimal precision (90%) and recall (85%).
- **Data Augmentation**: Used Roboflow for dataset augmentation, improving model accuracy and robustness.

## Dataset
The project utilized two datasets for training:
1. **Custom Dataset**: Captured using professional underwater cameras, comprising images of various underwater environments with different types of trash.
2. **Open-source Dataset**: JAMSTEC Underwater Plastic Dataset, an open-source dataset specifically for underwater plastic detection.

Both datasets were prepared, cleaned, and augmented using Roboflow to ensure better model performance.

## YOLO Models Used
- **YOLOv4**
- **YOLOv5**
- **YOLOv7**
- **YOLOv8**
- **YOLOv9**

## Results
Training with YOLOv9 provided the best results, as outlined below:
- **mAP**: 90.3%
- **Precision**: 90%
- **Recall**: 85%
- **Batch Size**: 24
- **Epochs**: 120

## Hyperparameter Tuning
- **Learning Rate**: 0.01
- **Batch Size**: 24
- **Epochs**: 120
- **Image Augmentation**: Rotation, scaling, flipping via Roboflow

## Tools & Technologies
- **YOLOv4 - YOLOv9**: Object detection models for trash detection.
- **Roboflow**: For data augmentation and preparation.
- **Python**: Core language for implementation.
- **PyTorch**: Used for model training.
- **OpenCV**: Image processing and manipulation.
- **Jupyter Notebooks**: For experimentation and model testing.



---
