## ASL Sign Language Classification (CNN)

Deep Learning project for classifying American Sign Language (ASL) hand signs (A–Z, 0–9) using a Convolutional Neural Network.

## Overview

36 Classes (Digits + Letters)

Image size: 200x200

Built with TensorFlow / Keras

CNN from scratch

## Model

Conv2D + BatchNorm + MaxPooling

Dropout for regularization

Dense layers

Softmax output (36 classes)

## Results

Training Accuracy: ~99%

Validation Accuracy: ~97%

Test Accuracy: ~94%

The model shows strong performance with stable convergence and good generalization.

## Technologies

Python, TensorFlow, Keras, NumPy, Pandas, Matplotlib, Scikit-learn

## Run
pip install -r requirements.txt
jupyter notebook

## Dataset

https://www.kaggle.com/datasets/ayuraj/asl-dataset?select=asl_dataset
