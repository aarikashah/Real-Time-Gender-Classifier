****Gender Classification using Transfer Learning (ResNet18)****

**Overview**

This project implements a real-time gender classification system using Deep Learning, Transfer Learning, and Computer Vision.

The model is built using a pretrained ResNet18 architecture in PyTorch and trained on the UTKFace dataset containing over 23,000 labeled facial images.

The system supports:

Image-based prediction
Real-time webcam inference
Video file inference
Face detection using MediaPipe
Real-time visualization using OpenCV

The final model achieved approximately 94% validation accuracy.

**Features**
Transfer Learning with ResNet18
Advanced Data Augmentation
Mixed Precision Training
Early Stopping
Learning Rate Scheduling
Real-Time Inference
OpenCV Integration
MediaPipe Face Detection
Confusion Matrix Evaluation

**Technologies Used**
Python
PyTorch
Torchvision
OpenCV
MediaPipe
NumPy
Matplotlib
scikit-learn

**Dataset**

Dataset Used:
UTKFace Dataset

The dataset contains facial images labeled with:

Age
Gender
Ethnicity

For this project, only gender labels were used.

**Model Architecture**

The project uses:

Pretrained ResNet18 backbone
Custom fully connected classifier
Dropout regularization
BCEWithLogitsLoss for binary classification

Additional training optimizations include:

ReduceLROnPlateau scheduler
Mixed precision training
Data augmentation pipeline

**Data Augmentation**

The training pipeline includes:

Random Horizontal Flip
Random Rotation
Color Jitter
Random Affine Transformations
Random Erasing

These augmentations improve model robustness and generalization.

**Training Results**

Final Validation Accuracy:
94%

Evaluation Metrics:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix

**Real-Time Inference**

The trained model performs:

Face detection using MediaPipe
Face preprocessing
Gender prediction using ResNet18
Real-time visualization using OpenCV

The system supports:

Webcam input
Video file input


**Future Improvements**

Larger and more diverse datasets
Fairness and bias evaluation

**Author**

Aarika Shah
