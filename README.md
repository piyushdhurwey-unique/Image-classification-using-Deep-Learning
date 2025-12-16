# Image-classification-using-deep-learning
## 📊 Project Overview
This project focuses on **binary image classification (Dog vs Cat)** using deep learning and compares a **custom-built CNN** with **transfer learning models (EfficientNetB0 and ResNet50)** implemented in TensorFlow/Keras.

## 🎯 Key Features
- **Custom CNN Architecture**: Designed and trained a CNN from scratch with Conv2D, Batch Normalization, MaxPooling, Dropout, and L2 regularization, achieving **~88% accuracy**.
- **Overfitting Control**: Identified overfitting through train–validation gaps and mitigated it using **Batch Normalization, Dropout, L2 regularization, and data normalization**.
- **Transfer Learning Models**: Implemented **EfficientNetB0 and ResNet50 (ImageNet pre-trained)** to compare performance with the custom CNN.
- **Model Evaluation & Comparison**: After resolving overfitting, EfficientNetB0 achieved **~50% accuracy** (underfitting), while **ResNet50 achieved ~62% accuracy**, showing better generalization due to residual connections.
- **Performance Analysis**: Conducted comparative analysis to understand the impact of architecture depth and pre-trained features on classification performance.
