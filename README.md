# Autism Emotion Recognition System

This project focuses on recognizing emotions in children with Autism Spectrum Disorder (ASD) using deep learning models and ensemble techniques.

---

## Overview

Emotion recognition in children with ASD is challenging due to subtle facial expressions. This project applies deep learning models and an ensemble approach to improve classification accuracy.


## Objectives

- Classify emotions: Angry, Happy, Neutral, Sad  
- Compare multiple deep learning models  
- Improve performance using ensemble learning  
- Achieve high generalization accuracy  

---

## Models Used

- MobileNet + Squeeze-and-Excitation (SE)
- Vision Transformer (ViT)
- Ensemble Model (MobileNet + SE + ViT + ResNet)

---

## 📊 Results Summary

| Model                | Train Acc (%) | Val Acc (%) | Test Acc (%) | Precision | Recall | F1 Score |
|---------------------|--------------|------------|-------------|----------|--------|----------|
| MobileNet + SE      | 93.47        | 87.32      | 85.58       | 0.86     | 0.86   | 0.86     |
| Vision Transformer  | 98.69        | 90.39      | 90.60       | 0.91     | 0.91   | 0.91     |
| **Ensemble Model**  | —            | —          | **98.55**   | **0.99** | **0.99** | **0.99** |



## Computation Time

- MobileNet + SE: 124.33 seconds  
- Vision Transformer: 2290.36 seconds  
- Ensemble Model: 111.19 seconds  



## Dataset

- Total images after preprocessing: **6872**
- Classes:
  - Angry
  - Happy
  - Neutral
  - Sad
- Balanced dataset using augmentation techniques  

Dataset not shared due to privacy concerns.

---

## Sample Outputs

(Add images in `/outputs` folder)
- Confusion Matrix  
- Accuracy Graphs  
- Grad-CAM Visualizations  

---

## How to Run

1. Clone the repository  
2. Install dependencies
3. Run notebook using:- VS Code / Jupyter / Colab  

---

## Key Features

- Data augmentation and balancing  
- Transfer learning models  
- Vision Transformer implementation  
- Ensemble learning for improved accuracy  
- High-performance classification (98.55%)  

---

