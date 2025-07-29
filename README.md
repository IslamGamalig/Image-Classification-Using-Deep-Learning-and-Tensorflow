

# 🧠 Image Classification Using Deep Learning and TensorFlow

This project demonstrates a complete workflow for training a deep learning model to classify images using TensorFlow and Keras. The model is trained on a custom dataset and goes through the full cycle of data preprocessing, augmentation, model building, training, evaluation, and prediction.

## 🚀 Features

- Load and preprocess image dataset using TensorFlow's `image_dataset_from_directory`.
- Apply data augmentation techniques to improve generalization.
- Build a CNN model using `Sequential` API.
- Train and evaluate the model with accuracy and loss tracking.
- Save the trained model for later use.
- Load and predict on new images.

## 🖼️ Sample Architecture

```text
Conv2D ➡ ReLU ➡ MaxPooling
Conv2D ➡ ReLU ➡ MaxPooling
Flatten ➡ Dense ➡ Dropout ➡ Dense (Output)
