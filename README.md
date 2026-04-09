# Skin-Cancer-Classification-DeepLearning
Advanced Skin Cancer Classification using Deep Learning (CNNs). Implements Transfer Learning with ResNet, DenseNet, and EfficientNet on medical imaging for binary and multi-class diagnosis
# Skin Cancer Classification System - Deep Learning Lab
**Lead AI_ML Engineer: Mahmoud Souliman**

## 📌 Project Overview
An advanced Deep Learning system designed for the automated classification of skin lesions into Benign and Malignant categories, as well as multi-class diagnosis. This project leverages state-of-the-art Convolutional Neural Networks (CNNs) to provide diagnostic support in dermatology.

## 🛠 Engineering Specifications (WDL Framework)
This implementation strictly follows professional deep learning standards for medical imaging:

* **Architectures Explored:** * **Custom CNN:** Baseline model for performance benchmarking.
    * **Transfer Learning:** Implementation of ResNet-101, DenseNet-101, and EfficientNet-B3 for feature extraction.
* **Data Pipeline:** * Sophisticated **Augmentations**: Flips, rotations, color jitter, and random resized cropping to improve generalization.
    * **Handling Imbalance:** Optimized loss functions and weighted sampling for medical accuracy.
* **Optimization:** Adam optimizer combined with advanced learning rate scheduling.

## 🚀 Key Technical Challenges Solved
* **Medical Accuracy:** Achieved high F1-Score and ROC-AUC by fine-tuning backbones on medical datasets.
* **Error Analysis Module:** Developed a custom visualization script to analyze "Incorrectly Predicted" samples, allowing for qualitative clinical auditing.
* **Inference Optimization:** Conducted experiments to balance model parameters (M) vs. inference speed (img/s).

## 📊 Hardware & Environment
* **Compute:** Trained using **NVIDIA T4 GPU** acceleration.
* **Platform:** Developed and tested on Google Colab for cloud-based scalability.
* **Metrics:** Macro-Precision, Macro-Recall, and Macro-F1 Score.

## 📁 Repository Structure
* `Model/`: Core Jupyter Notebook with full training logs.
* `Results/`: Evaluation metrics and performance comparison tables.

---
**Developed as part of the Deep Learning (WDL) Specialization.**
*Copyright © 2026 Mahmoud Souliman. All rights reserved.*
