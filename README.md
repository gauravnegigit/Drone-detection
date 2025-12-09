# Drone Detection

# Project Overview 
This project implements a binary image classification system to distinguish between drones and non-drones using deep learning techniques. The model leverages transfer learning with ResNet50 architecture and provides comprehensive performance analysis including uncertainty estimation. **Key Features:** - Transfer learning with pre-trained ResNet50 - Data augmentation for improved generalization - Using Dropout and Batch Normalization for better results - Statistical analysis - Comprehensive visualization and evaluation metrics **Dataset:** Birds vs Non-Drone image dataset with balanced binary classification **Objective:** Build a robust classifier that can accurately distinguish between birds and drones while providing confidence estimates for predictions.

# Data Augmentation Configuration
Implementing data augmentation techniques to improve model generalization. Random transformations include horizontal/vertical flips, rotation, and zoom operations to create diverse training samples.

# Model Architecture
Building a transfer learning model using EfficientNetB0 as the backbone. The architecture includes data augmentation, global average pooling, dropout for regularization, and a final dense layer for binary classification.

# Model Training
Training the model for 15 epochs with both training and validation datasets. The training history is stored for later analysis and visualization.

# Training Results Visualization
Visualizing training progress through accuracy and loss curves. These plots help identify overfitting, underfitting, and overall model convergence patterns.

# Model Evaluation
Comprehensive evaluation of model performance on test data including accuracy metrics, confusion matrix visualization, and detailed classification report.
