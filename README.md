# Image Forgery Detection

## Project Overview

This repository contains two projects focusing on detecting image forgery using different approaches and deep learning models. The aim is to classify images as either authentic or tampered, leveraging the power of deep learning architectures.

## Notebooks

### 1. InceptionV3 and VGG16 for Image Forgery Detection

- **Objective**: Utilize pre-trained models InceptionV3 and VGG16 to detect forged images.
- **Dataset**: The CASIA image tampering detection dataset is used to train and evaluate the models.
- **Main Steps**:
  - Download and prepare the dataset.
  - Preprocess the images using data augmentation techniques.
  - Train deep learning models using InceptionV3 and VGG16 architectures.
  - Evaluate the models based on precision and recall metrics.

### 2. ELA and DenseNet121 for Image Forgery Detection

- **Objective**: Implement Error Level Analysis (ELA) and DenseNet121 to identify image tampering.
- **Methodology**:
  - Convert images using ELA to highlight compression artifacts.
  - Use DenseNet121 to classify ELA-processed images as authentic or tampered.
  - Train and fine-tune the model using data augmentation and early stopping.
  - Evaluate performance using confusion matrices and other classification metrics.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required libraries: TensorFlow, NumPy, Matplotlib, Scikit-learn, Pillow, and other standard Python libraries.
