# traffic-sign-recognition-cnn

CNN-based traffic sign classifier trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

## Overview
Classifies traffic signs across 43 categories using a custom CNN architecture, achieving 99.3% test accuracy. Deployed via an interactive Gradio interface for real-time image classification.

## Dataset
GTSRB — ~39,200 images across 43 sign classes (via Kaggle)

## Architecture
Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Dropout → Dense (softmax)
Trained for 15 epochs with early stopping and data augmentation (rotation, zoom, shift).

## Results
99.3% test accuracy

## Tech Stack
Python, TensorFlow/Keras, OpenCV, Gradio
