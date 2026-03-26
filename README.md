# Dental-Caries-Detection-CNN

An automated system for detecting tooth decay (caries) from intraoral images using Convolutional Neural Networks (CNN). This project aims to assist dental professionals in early diagnosis and screening of dental health issues.

## ┬┐ Project Overview
Early detection of dental caries is crucial for maintaining oral health and preventing further complications. This project leverages deep learning techniques to classify dental images into various stages of tooth decay.

## ┬┐ Features
- **Deep Learning Model**: CNN architecture optimized for dental image classification.
- **Automated Pipeline**: Includes data preprocessing, training, and evaluation scripts.
- **Dataset Support**: Structured for training on varied intraoral image datasets.

## ┬┐ Project Structure
- `notebooks/`:
    - `Tooth_Decay_CNN_Training.ipynb`: Main notebook for model architecture and training.
    - `hackdata.ipynb`: Data experimentation and processing script.
- `data/`:
    - `teeth_dataset/`: Contains partitioned train/test images and CSV metadata.
    - `test.jpg`: Sample image for inference testing.

## ┬┐ Getting Started

### Prerequisites
- Python 3.8+
- TensorFlow / Keras
- OpenCV
- Pandas, NumPy, Matplotlib

### Usage
1. Clone the repository.
2. Navigate to `notebooks/`.
3. Open `Tooth_Decay_CNN_Training.ipynb` in Jupyter or Google Colab to train the model.

## ┬┐ Dataset
The dataset includes labeled images of teeth categorized into:
- **Healthy**
- **Caries (Decay)**

Refer to `data/teeth_dataset/` for the training and testing sets.

---
*Created by DinhLucent - 2022 (Updated 2026)*