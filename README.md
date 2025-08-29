# 🎨 Conditional Image Generation using GaussianGAN (GauGAN)

## 📌 Project Overview
This project implements **Conditional Image Generation** using a **Gaussian-based Generative Adversarial Network (GAN)** inspired by NVIDIA’s **GauGAN**.  
The model learns to generate **photorealistic images from segmentation maps**, conditioned on semantic labels.  

## 📂 Repository Structure
   - Final_Gaugan_Training.ipynb for Main training & evaluation script
   - Datasets for Dataset info and download links
   - Output Vs Ground Truth for generated outputs, ground truth images and segmentation label maps
   - Project_Report
   - README.md for Project documentation


## 📂 Dataset
Two datasets were used for training and evaluation.  
Links are provided inside [`Dataset/README.md`](Dataset/README.md).

- `images/` → real images  
- `segmentation_map/` → RGB visualization of segmentation  
- `segmentation_labels/` → single-channel labels (IDs ∈ `[0…NUM_CLASSES-1]`, `255` = void class)  
