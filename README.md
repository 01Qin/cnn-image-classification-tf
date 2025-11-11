# CNN Image Classification

This project demonstrates two convolutional neural network approaches for image classification tasks using TensorFlow and Keras.

## Overview
1. **CNN from Scratch (CIFAR-10)**
   - Custom-built convolutional neural network trained on CIFAR-10.
   - Achieved ~70–75% test accuracy after tuning.
   - Includes normalization, visualization, and performance evaluation.

2. **Transfer Learning (Cats vs Dogs)**
   - Used pre-trained **MobileNetV2** as a frozen feature extractor.
   - Added a custom classifier head.
   - Fine-tuned final layers to boost validation accuracy.

## Key Features
- End-to-end pipeline: loading → preprocessing → augmentation → training → evaluation.
- Demonstrates transfer learning and feature extraction.
- Model saving and reloading.
- Performance plots and metrics (accuracy, F1-score).

## Environment
Install dependencies:
```bash
pip install -r requirements.txt

