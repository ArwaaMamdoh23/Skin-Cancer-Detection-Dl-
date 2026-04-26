# Skin Cancer Classification

## Overview
Deep learning project to classify skin cancer images into:
- Benign
- Malignant

## Dataset
Images organized into two folders:

├── Benign/
├── Malignant/

Dataset link:
https://www.kaggle.com/datasets/arwaamamdoh203203/skincancer-classification/data

## Approaches
Two models were used:
- TensorFlow (EfficientNetB1 / MobileNetV2)
- PyTorch (ResNet18)

Both use transfer learning and image augmentation.

## Preprocessing
- Resize images to 224×224
- Normalization
- Data augmentation (rotation, zoom, flip)

## Models
- EfficientNetB1 / ResNet18 backbone
- Fully connected layers + Dropout
- Softmax output

## Results
- Train Accuracy: 99.85%
- Validation Accuracy: 93.02%
- Test Accuracy: 99.39%

## Libraries
TensorFlow, PyTorch, OpenCV, NumPy, Pandas, Matplotlib, Scikit-learn

## Author
Arwaa Mamdoh
