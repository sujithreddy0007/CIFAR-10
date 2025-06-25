# 🧠 CNN for CIFAR-10 Image Classification

This project implements a Convolutional Neural Network (CNN) to classify images from the **CIFAR-10** dataset — a standard benchmark dataset in computer vision containing 60,000 32x32 color images in 10 classes.

---

## 📦 Dataset: CIFAR-10

- **60,000** images total
  - 50,000 for training
  - 10,000 for testing
- **10 classes**:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

---

## 🚀 Features

- Custom CNN architecture built using TensorFlow/Keras
- Uses **ReLU** activations and **softmax** for classification
- Includes **data augmentation** for better generalization
- Plots training & validation accuracy/loss
- Evaluates performance using **confusion matrix** & **classification report**
- Easily extensible for other image classification tasks

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn

---

## 🧪 Model Architecture (Example)

```text
Input (32x32x3)
→ Conv2D (32 filters, 3x3) + ReLU  
→ MaxPooling2D (2x2)  
→ Conv2D (64 filters, 3x3) + ReLU  
→ MaxPooling2D (2x2)  
→ Flatten  
→ Dense (128) + ReLU  
→ Dense (10) + Softmax  
