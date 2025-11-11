# CNN Image Classification using TensorFlow

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-API-red?logo=keras)](https://keras.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)

This repository demonstrates two convolutional neural network (CNN) pipelines for image classification tasks:
1. A **CNN built from scratch** on CIFAR-10.
2. A **Transfer Learning model** using **MobileNetV2** for Cats vs Dogs.

---

## 📁 Repository Structure
cnn-image-classification-tf/


---

## Features
- CNN model from scratch using **Conv2D**, **MaxPooling2D**, and **Dense** layers.  
- Transfer learning with **MobileNetV2** pretrained on ImageNet.  
- Data preprocessing, normalization, and augmentation.  
- Confusion matrix and classification report.  
- Model saving and fine-tuning demonstration.  

---

## Datasets

| Dataset | Source | Classes | Image Size |
|----------|---------|----------|-------------|
| CIFAR-10 | `keras.datasets.cifar10` | 10 | 32×32 |
| Cats vs Dogs | `tensorflow_datasets.cats_vs_dogs` | 2 | 160×160 |

---

