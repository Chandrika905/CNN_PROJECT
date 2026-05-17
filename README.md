CNN with TensorFlow — Food Image Classification

A deep learning computer vision project built using TensorFlow and Convolutional Neural Networks (CNNs) to classify food images.

This project focuses on binary image classification using the Pizza vs Steak subset of the Food101 dataset.

Project Overview

Computer Vision enables machines to understand and interpret visual data. In this project, a CNN model is trained to identify whether an image contains:

🍕 Pizza
🥩 Steak

The notebook walks through the complete deep learning workflow:

Loading image data
Visualizing samples
Preprocessing images
Building CNN architectures
Training models with TensorFlow
Evaluating performance
Making predictions on new images

Dataset

The project uses a modified version of the Food101 Dataset.

Original Dataset:

Food101 contains 101 food classes.
This project uses only 2 classes:
Pizza
Steak

Dataset Source:

Kaggle Food101 Dataset

Workflow
Import libraries
Load image dataset
Explore and visualize data
Preprocess images
Normalize pixel values
Build CNN model
Compile and train model
Evaluate model performance
Make predictions
Visualize prediction results

Evaluation Metrics

The model performance is evaluated using:

Accuracy
Training Loss
Validation Loss
