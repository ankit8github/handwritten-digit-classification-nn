
# Handwritten Digit Classification using Neural Networks
This project implements a neural network model to classify handwritten digits (0–9) using the MNIST dataset.

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib, Seaborn

## Approach
- Normalized grayscale images for stable training
- Flattened 28×28 images into 784-dimensional vectors
- Built and compared:
  - Single-layer neural network
  - Neural network with a hidden ReLU layer
- Evaluated performance using accuracy and a confusion matrix

## Results
- Achieved ~97% accuracy with a hidden-layer model
- Identified misclassification patterns using a confusion matrix heatmap

