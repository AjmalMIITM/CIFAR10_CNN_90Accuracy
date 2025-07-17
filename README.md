# CIFAR10_CNN_90Accuracy
PyTorch implementation of a CNN for CIFAR-10 image classification achieving ~90.12% test accuracy with data augmentation, batch normalization, dropout, and learning rate scheduling.

## ✅ Highlights

- 📦 **Dataset**: CIFAR-10  
  - 60,000 color images (32x32 pixels)
  - 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

- 🧠 **Model**: Custom Convolutional Neural Network  
  - Includes **Batch Normalization** and **Dropout** layers for regularization

- 🛠️ **Training Setup**:  
  - Optimizer: **Adam**
  - Learning Rate Scheduler: **StepLR**
  - Epochs: **30**
  - Batch Size: **128**

- 🏎️ **Training Platform**: GPU (CUDA)

- 🎯 **Final Test Accuracy**: **~90.12%**

## 📊 Final Results

- ✅ Final Test Accuracy: **90.12%**
- 📉 Final Training Loss: **0.1452**
- 📈 Model demonstrates strong generalization after 30 epochs

### 📌 Training Strategy
- Data Augmentation:
  - **Random Horizontal Flip**
  - **Random Cropping with Padding**
- Regularization:
  - **Batch Normalization**
  - **Dropout (0.25 - 0.5)**
- Learning Rate Scheduler:
  - Step down by **gamma = 0.1 every 10 epochs**

### 🧪 Sample Epoch Loss Progress

| Epoch | Loss  |
|-------|--------|
| 1     | 1.6576 |
| 10    | 0.4919 |
| 20    | 0.2557 |
| 30    | 0.1452 |
