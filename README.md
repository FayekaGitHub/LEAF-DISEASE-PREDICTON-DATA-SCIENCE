# Leaf Disease Prediction 
## Overview

This project focuses on predicting plant diseases using images of leaves. It involves training Convolutional Neural Networks (CNNs) to classify leaf images into various disease categories. The project includes both a custom CNN model and a pre-trained EfficientNet model, and combines their predictions for improved performance.

## Model Training
### Custom CNN Model
   Model Architecture: Defined a custom CNN with convolutional and pooling layers.

### EfficientNet Model
   Pre-trained Model: Used EfficientNetB0 with additional classification layers.

### Combined Prediction
  Combined predictions from both models by averaging them to enhance classification accuracy.

## Visualizations
### The project includes the following visualizations:
##### 1. Number of Images per Class (Training & Validation Datasets):
  - Bar charts showing the distribution of images across different classes for both the training and validation datasets.
##### 2. Healthy vs. Diseased Images:
   - Bar charts comparing the number of healthy and diseased images in both the training and validation datasets.
##### 3. Model Accuracy and Loss:
   - Line plots of training and validation accuracy and loss over epochs for the custom CNN model.
##### 4. Confusion Matrix:
   - A heatmap of the confusion matrix to visualize the classification performance of the ensemble model.

## Evaluation
### Metrics:
Accuracy, precision, recall, and F1 score.
### Confusion Matrix: 
Visualizes model performance across different classes.
