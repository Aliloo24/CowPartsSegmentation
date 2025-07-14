# CowPartsSegmentation
This repository contains the officiel dataset, trained models, and evaluation scripts for our cattle part segmentation framework based on a modified DeepLabV3+ architecture with ResNet backbones, ASPP, and MSAM attention. The model is designed for precision segmentation of head, body, legs, and tail regions in real-world farm scenarios.

# System Architecture
<img width="1115" height="638" alt="figure_2F" src="https://github.com/user-attachments/assets/e796d560-f0a9-4b80-b77c-a3e785b7dbb3" />

# Dataset
The generated dataset with masks is available upon request at: https://drive.google.com/drive/folders/1Lo9P2qrSCJMI-Ft2cEjho9qVUShZnN4J?usp=drive_link 

# Dataset Samples with Masks
![figure_1](https://github.com/user-attachments/assets/743082b3-2e83-43d8-a032-83038c33a08b)

# Colab Notebook: Cattle Part Segmentation Pipeline
A Jupyter notebook containing complete walkthrough of our proposed semantic segmentation framework for cattle anatomical part detection. It includes:
  - Automatic generation of segmentation masks from bounding box annotations.
  - Visualization of dataset samples and their corresponding masks.
  - Network architecture overview (ResNet-50 + ASPP + MSAM).
  - Model training setup and configuration.
  - Visual evaluation of segmentation results on test set samples.

Optimized for use in Google Colab to facilitate reproducibility and experimentation, download dataset, model.pth file and update paths as needed.

# Qualitative Segmentation Results
![figure_6](https://github.com/user-attachments/assets/3ea030b5-129e-495b-b9b5-ab02a7d79a1f)

