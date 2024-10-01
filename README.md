# Brain Tumor Segmentation using U-Net in PyTorch

## Overview
This repository contains a PyTorch implementation of a U-Net-based deep learning model for brain tumor segmentation from MRI images. The model is designed to accurately identify and segment tumor regions in MRI scans using a robust neural network architecture.

## Features
- **Deep Learning Model**: Utilizes the U-Net architecture for precise segmentation.
- **Data Augmentation**: Employs Albumentations library for advanced image augmentation to improve generalization.
- **Training Pipeline**: Trained on a dataset of over 3,000 MRI images with labels for tumors and non-tumors.
- **Tools & Libraries**: Built with PyTorch, Torchvision, and CUDA for performance optimization.

## Dataset
The dataset used in this project consists of MRI images with labeled tumor regions. The images are pre-processed and augmented to improve model performance.  
It can be found [here](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation/data).
