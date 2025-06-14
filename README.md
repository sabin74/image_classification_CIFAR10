# 🧠 CIFAR-10 Image Classification using CNN & Transfer Learning

This project demonstrates how to build a deep learning image classifier using the CIFAR-10 dataset. Two approaches are implemented:
1. A custom Convolutional Neural Network (CNN)
2. A transfer learning model using VGG16

---

## 📊 Dataset Overview

- **Dataset:** CIFAR-10
- **Classes (10):** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- **Image Shape:** (32, 32, 3)
- **Train/Test Split:** 50,000/10,000

---

## 🚀 Model Architectures

### Custom CNN

- 3 Convolutional blocks with MaxPooling
- Batch Normalization and Dropout
- Dense layers for final classification

### Transfer Learning (VGG16)

- `VGG16` with `include_top=False`
- Input images resized to (224x224)
- GlobalAveragePooling + Dense layers

---

## 🛠️ Key Techniques

- CNN Architecture
- Data Augmentation
- Regularization (Dropout, L2)
- Batch Normalization
- Transfer Learning
- Callbacks (EarlyStopping, ModelCheckpoint)
- Evaluation (Confusion Matrix, Classification Report)
