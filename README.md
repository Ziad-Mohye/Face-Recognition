# Face Recognition System

This project implements a face recognition system using both deep learning and classical computer vision techniques. The goal is to compare the performance of different models on the CASIA-WebFace dataset.

## Overview
- Built and trained **MLP** and **CNN encoder-decoder networks** using TensorFlow.
- Implemented the classical **Eigenfaces** approach.
- Used a **neural network classifier** to compare feature representations from different methods.

## Dataset
- **CASIA-WebFace** dataset used for training and evaluation.
- Preprocessing includes face alignment and resizing.

## Models Used
- MLP Encoder-Decoder
- CNN Encoder-Decoder
- Eigenfaces (PCA)
- Neural network classifier for evaluation

## Tools & Libraries
- TensorFlow
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib

## Evaluation
- Compared recognition accuracy across all methods.
- Visualized reconstructed faces and performance metrics.

## How to Run
1. Clone the repo
2. Install dependencies from `requirements.txt`
3. Run `Face Recognition.ipynb` to train and evaluate models

