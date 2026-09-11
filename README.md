# Aedes Mosquito Wingbeat Classification

This project uses **deep learning to classify Aedes mosquito species based on acoustic wingbeat signals**. The audio signals are converted into spectrogram images and used to train and compare several deep learning architectures.

## Models

Five deep learning models are evaluated:

* ResNet
* DenseNet
* MobileNet
* Capsule Network (CapsNet)
* Vision Transformer (ViT)

## Project Workflow

**Wingbeat Audio → STFT → Spectrogram → Deep Learning Model → Species Classification**

The wingbeat audio signals are converted into spectrograms using the **Short-Time Fourier Transform (STFT)**. The generated spectrograms are then used as input to the deep learning models.

## Model Evaluation

The models are compared using classification performance metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Tools & Technologies

* Python
* PyTorch
* Deep Learning
* STFT
* Audio Signal Processing
* Computer Vision

## Objective

The objective of this project is to compare different deep learning architectures and identify the most effective model for **Aedes mosquito species classification using acoustic wingbeat spectrograms**.

## Author

**Nur Faizah Hambali**
