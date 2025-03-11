# MSR-Net-for-Satellite-Image-Segmentation
Overview:
This project implements MSR-Net for satellite image segmentation, leveraging multi-scale feature extraction and residual learning to enhance segmentation accuracy. The model is built using PyTorch and processes satellite images to generate segmented outputs.

Features:

-Multi-scale feature extraction with residual learning.
-Implements an Inception-based block for improved segmentation accuracy.
-Uses PyTorch for deep learning and data processing.
-Dataset loading and augmentation using torchvision.transforms.

Dataset:
The project uses satellite imagery datasets stored in the following directories:
Training Data: /kaggle/input/train
Validation Data: /kaggle/input/valid
Test Data: /kaggle/input/test
Color Codes: /kaggle/input/class_dict.csv

Links:
Dataset: https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset
MSR-Net Architecture Paper: https://link.springer.com/content/pdf/10.1007/s00034-022-02190-5.pdf
