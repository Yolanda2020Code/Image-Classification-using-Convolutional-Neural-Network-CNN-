# Image Classification using Convolutional Neural Network (CNN)

This project provides a foundational structure to build an image classification model using a Convolutional Neural Network (CNN) with TensorFlow 2.x and Keras. The code uses the CIFAR-10 dataset for demonstration purposes.

## Description:
- The model consists of a sequential stack of convolutional and max-pooling layers followed by dense layers.
- The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes.
- The model undergoes training on the dataset and then saves it for future use.

## Requirements:
- tensorflow>=2.0

## Usage:
1. Ensure you have TensorFlow 2.x installed.
2. Run the provided code to train the model on the CIFAR-10 dataset.
3. Save the model using the in-built save function.
4. For a real-world scenario, integrate this model into applications for image classification tasks.

**Note**: The code is meant to demonstrate the structure of a basic CNN model. Enhancements like data augmentation, dropout layers, and hyperparameter tuning can further improve the model's performance.

