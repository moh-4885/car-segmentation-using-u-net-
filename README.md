
# Car Segmentation Model for Carvana Image Masking Challenge
This repository contains a car segmentation model developed for the Carvana Image Masking Challenge on Kaggle. The model uses the U-Net architecture implemented from scratch to accurately mask and identify vehicles in images.

## Project Overview
The goal of this project is to build a deep learning model that can perform pixel-wise segmentation to separate cars from the background in images. Using U-Net, a convolutional network designed for biomedical image segmentation, we aim to achieve high accuracy in detecting vehicle outlines and providing precise masks.

## Key Features
- Implementation of U-Net architecture from scratch using Python and TensorFlow/PyTorch.
- Trained on the Carvana dataset, which contains images of cars with corresponding masks.
- Evaluation metrics include Intersection over Union (IoU) and pixel accuracy.
## Dataset Preparation
Download the Carvana dataset from Kaggle:
<a href ="https://www.kaggle.com/c/carvana-image-masking-challenge">Carvana Image Masking Challenge</a>
## Model Architecture
The U-Net architecture consists of a contracting path to capture context and a symmetric expanding path that enables precise localization. Notable components include:

- Convolutional layers with ReLU activation.
- Max pooling and upsampling layers.
- Skip connections to preserve spatial information.
## References
Ronneberger, O., Fischer, P., & Becker, A. (2015). U-Net: Convolutional Networks for Biomedical Image Segmentation. In Medical Image Computing and Computer-Assisted Intervention (MICCAI).
