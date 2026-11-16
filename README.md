# Handwritten Digit Classification using CNN

## Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset.

## Features
- CNN built from scratch
- Trained on the MNIST dataset
- Achieves approximately 99% training accuracy and 98–99% test accuracy
- Supports prediction on custom images

## Dataset
- MNIST
- 60,000 training images
- 10,000 testing images
- Image size: 28×28 grayscale

## Model Architecture

Conv2D (1 → 32)
↓
ReLU
↓
MaxPool
↓
Conv2D (32 → 64)
↓
ReLU
↓
MaxPool
↓
Flatten
↓
Linear (3136 → 128)
↓
ReLU
↓
Linear (128 → 10)

## Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Results
- Training Accuracy: 99%+
- Test Accuracy: 98–99%

## How to Run

```bash
pip install -r requirements.txt
```

Train:

```bash
python train.py
```

Predict:

```bash
python predict.py
```

## Future Improvements

- Data augmentation
- Streamlit web application
- Digit drawing canvas
- Batch Normalization
- Dropout