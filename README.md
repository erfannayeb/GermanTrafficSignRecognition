# German Traffic Sign Recognition

This project focuses on the classification and detection of traffic signs using Convolutional Neural Networks (CNN) and YOLOv5 on the **German Traffic Sign Benchmark (GTSRB)** dataset. The GTSRB is a well-established dataset for multi-class, single-image classification challenges, originally introduced at the International Joint Conference on Neural Networks (IJCNN) 2011.

## Dataset Overview
The German Traffic Sign Benchmark dataset has the following properties:
- **Single-image, multi-class classification problem**
- **More than 40 classes**
- **Over 50,000 images in total**
- **Large, lifelike database**

## Approach
This project employs two key deep learning models for traffic sign recognition:
1. **Convolutional Neural Networks (CNNs)**: Used for image classification, predicting the category of a given traffic sign.
2. **YOLOv5 (You Only Look Once v5)**: Applied for object detection, identifying and localizing traffic signs within images.

## Implementation Details
- **CNN-based Classification**:
  - Preprocessing and augmentation applied to improve generalization.
  - Custom CNN model trained on GTSRB for multi-class classification.
  - Evaluation metric include accuracy.
  
- **YOLOv5-based Detection**:
  - Dataset annotation and preprocessing for YOLOv5 compatibility.
  - Training on GTSRB for real-time traffic sign detection.
  - Performance evaluation using mAP (mean Average Precision).
