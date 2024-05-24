# Melanoma Detection
ML Model with Deep Learning and Neural Networks to evaluate the chance that a mole is cancerous (Melanoma).

## Objective
This project aims to leverage deep learning techniques to accurately classify skin lesions as benign or malignant based on image data. Early and reliable detection of melanoma can significantly improve treatment outcomes.

## Dataset
Utilizing the [Melanoma Skin Cancer Dataset of 10,000 Images](https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images) from Kaggle, which includes diverse skin lesion images categorized into benign and malignant classes.

## Methods/Techniques Used
- **Early Stopping**:
  - **Purpose**: Prevent overfitting and stop training when performance on validation data stops improving, measured by validation loss.
- **Image Data Augmentation** (Using Keras' `ImageDataGenerator`):
  - **Operations**: Rescale, rotate, horizontal flip, and more.
  - **Purpose**: Enhance model robustness and prevent overfitting by introducing variations in the training dataset.

## CNN Architecture (Using TensorFlow and Keras)
- **Layers**: 3 Convolutional layers with increasing filter sizes (32, 64, 128).
- **Pooling**: MaxPooling layers to reduce spatial dimensions and computational cost.
- **Output**: Sigmoid activation to output the probability of malignancy.

## Usage
Use the h5 model file within this repo!

## Results
- loss: 0.2900
- accuracy: 0.8799
