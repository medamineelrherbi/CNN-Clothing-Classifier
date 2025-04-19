# Fashion Forward Garment Classifier

## Project Overview
This project implements an AI-based garment classification system for Fashion Forward, an e-commerce clothing retailer. The system uses a Convolutional Neural Network (CNN) to automatically categorize clothing items from the FashionMNIST dataset into 10 distinct categories, helping with product organization and inventory management.

## Dataset
The model is trained on the FashionMNIST dataset, which contains:
- 60,000 training images
- 10,000 test images
- 10 categories: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot
- Grayscale images of size 28×28 pixels

## Model Architecture
The CNN model consists of:
1. Feature extraction layers:
   - Two convolutional layers with ReLU activation
   - Max pooling layers for downsampling
2. Classification layer:
   - Fully connected layer for final classification

## Metrics
The model is evaluated using:
- Accuracy: Overall correctness of predictions
- Precision: Ratio of true positives to all predicted positives (per class)
- Recall: Ratio of true positives to all actual positives (per class)

## Results
After training for 2 epochs, the model achieves:
- Accuracy: ~0.85 (may vary slightly)
- Class-wise precision and recall scores

## Requirements
To run this project, you'll need:
- Python 3.x
- PyTorch
- torchvision
- torchmetrics

## Installation
```bash
pip install torch torchvision torchmetrics
