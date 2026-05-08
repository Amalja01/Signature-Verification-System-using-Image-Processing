# Signature Verification System using Image Processing and Siamese Neural Networks

## Overview
This project is an AI-based handwritten signature verification system developed using Image Processing and Deep Learning techniques. The system compares two signature images and determines whether the test signature is genuine or forged.

The project combines traditional image preprocessing methods with a Siamese Convolutional Neural Network (CNN) to achieve reliable signature verification performance.

---

## Features
- Signature preprocessing pipeline
- Noise removal and enhancement
- Skeletonization for stroke normalization
- Feature extraction using:
  - Hu Moments
  - Local Binary Patterns (LBP)
  - Structural Similarity Index (SSIM)
- Siamese Neural Network for similarity learning
- Genuine vs Forgery classification
- Interactive Gradio web interface
- Performance evaluation using:
  - ROC Curve
  - Precision-Recall Curve
  - Confusion Matrix

---

## Technologies Used
- Python
- OpenCV
- TensorFlow / Keras
- Scikit-image
- Scikit-learn
- NumPy
- Matplotlib
- Gradio

---

## Image Processing Pipeline
The preprocessing pipeline includes:

1. Image resizing
2. Grayscale conversion
3. CLAHE enhancement
4. Gaussian blur
5. Adaptive thresholding
6. Morphological closing
7. Noise removal
8. Skeletonization
9. Feature extraction

---

## Model Architecture
The project uses a Siamese CNN architecture that learns similarity between two signature images.

### Key Components
- Shared CNN encoder
- Euclidean distance layer
- Contrastive loss function
- Similarity threshold classification

---

## Performance Metrics
The system evaluates performance using:
- Accuracy
- Precision
- Recall
- F1-Score
- FAR (False Acceptance Rate)
- FRR (False Rejection Rate)
- ROC-AUC

---

## User Interface
A Gradio-based interface allows users to:
- Upload a reference signature
- Upload a test signature
- Verify authenticity instantly

---

## Installation

```bash
pip install opencv-python-headless matplotlib scikit-learn tensorflow scikit-image gradio Pillow tqdm
