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

## 🧠 Model Summary
DUCK-Net is a convolutional neural network architecture tailored for biomedical segmentation tasks. It uses dense skip connections and efficient up/downsampling strategies to maintain spatial accuracy while capturing contextual information across MRI volumes.

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

