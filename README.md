# 🧠 Brain Tumor Segmentation using DUCK-Net

## 📌 Project Overview
This project focuses on automating brain tumor detection in MRI scans using the DUCK-Net deep learning architecture and the BraTS dataset. The objective is to build a system that can accurately segment and outline tumor regions to assist radiologists in making faster, more consistent diagnostic decisions, reducing reliance on time-consuming manual analysis.

## 🧪 Problem Statement
Segmenting brain tumors from MRI scans manually is time-intensive and subject to interpretation variability. This project addresses this challenge using a deep learning model that performs precise and automated segmentation, identifying key tumor subregions like the enhancing tumor, tumor core, and whole tumor.

## 🧰 Technologies Used
- Python
- TensorFlow
- DUCK-Net Architecture
- BraTS Dataset
- Deep Learning
- Image Segmentation

## 📊 Project Highlights
- Leveraged BraTS dataset with multimodal MRI scans (T1, T1CE, T2, FLAIR).
- Implemented DUCK-Net using TensorFlow and Keras.
- Trained the model to segment tumor regions from 3D volumes.
- Evaluated performance using Dice Coefficient and Intersection over Union (IoU).
- Visualized predicted vs. ground truth segmentation masks for validation.

## 🔄 Project Workflow
1. MRI Data preprocessing and normalization  
2. Dataset splitting for training, validation, and testing  
3. Model definition and training using DUCK-Net  
4. Evaluation and visualization of segmentation performance

## 🧠 DUCK-Net Architecture

The architecture used for this project is DUCK-Net — a specialized convolutional neural network designed for high-precision biomedical image segmentation. It incorporates dense skip connections and optimized downsampling/upsampling blocks to preserve spatial features.

![image](https://github.com/user-attachments/assets/f09c54b3-4ba0-49c0-894b-e6e62bdbf45a)

## 🧪 Sample Predictions

Below is a visual comparison between the ground truth tumor segmentation and the DUCK-Net model's prediction. This showcases how well the model identifies tumor boundaries in MRI scans.

![image](https://github.com/user-attachments/assets/06473fd4-75ab-4591-8b72-1061f0248e06)

## 🔄 Training Pipeline Overview

The workflow includes preprocessing the BraTS dataset, training the DUCK-Net architecture, and evaluating segmentation results using standard metrics like Dice and IoU.

![Training Pipeline](images/training_pipeline.png)
