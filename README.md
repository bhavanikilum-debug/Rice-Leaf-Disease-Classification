# Rice Leaf Disease Classification

## Project Overview

This project focuses on classifying rice leaf diseases using Deep Learning and Convolutional Neural Networks (CNN).

The objective is to build an image classification model that can identify different rice leaf disease categories from leaf images.

The project demonstrates an end-to-end Deep Learning workflow including image preprocessing, data augmentation, CNN model development, training, validation, and performance evaluation.

## Objective

The main objective of this project is to automatically classify rice leaf images into their respective disease categories using a Convolutional Neural Network.

This type of system can help support early identification of crop diseases and assist farmers in taking appropriate preventive actions.

## Dataset

The dataset consists of images of rice leaves belonging to different disease categories.

The images were used for training and validating the Deep Learning model.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook
- Convolutional Neural Network (CNN)

## Project Workflow

### 1. Data Loading

The rice leaf image dataset was loaded and organized according to the different disease classes.

### 2. Image Preprocessing

The images were preprocessed before being provided to the CNN model.

The preprocessing included:

- Resizing images
- Normalizing pixel values
- Preparing images for model training

### 3. Data Augmentation

Data augmentation was applied to increase the variety of training images and improve the model's ability to generalize.

Augmentation techniques help the model learn from different variations of the same image.

### 4. Train and Validation Data

The dataset was divided into training and validation data.

The training data was used to learn the patterns associated with different rice leaf diseases, while the validation data was used to evaluate the model during training.

### 5. CNN Model

A Convolutional Neural Network was developed for image classification.

The CNN architecture uses convolutional layers to extract important visual features from rice leaf images.

Activation functions such as **ReLU** were used in the hidden layers, and **Softmax** was used in the output layer for multi-class classification.

### 6. Model Compilation

The model was compiled using:

- **Adam optimizer**
- **Categorical classification loss**
- **Accuracy as the evaluation metric**

### 7. Model Training

The CNN model was trained for multiple epochs using the augmented training images.

Training and validation accuracy and loss were monitored during the training process.

## Model Performance

The model achieved approximately **69.5% validation accuracy after 15 epochs** during the training process.

The model performance can be further improved through additional tuning, data augmentation, and architectural improvements.

## Key Findings

- CNNs are effective for extracting visual features from plant leaf images.
- Data augmentation helps increase training data diversity.
- ReLU activation helps the network learn non-linear image features.
- Softmax is suitable for multi-class disease classification.
- The Adam optimizer provides an effective optimization approach for CNN training.

## Advantages

- Automated disease classification
- Reduces the need for manual visual inspection
- Can support early disease identification
- Can be extended to other crop disease classification problems

## Limitations

- Model performance depends on the quality and diversity of the image dataset.
- More training data may be required for better generalization.
- Similar-looking diseases can be difficult to distinguish.
- Further model tuning is required to achieve higher accuracy.

## Future Improvements

The project can be further improved by:

- Increasing the size and diversity of the dataset
- Applying advanced data augmentation
- Hyperparameter tuning
- Using transfer learning models such as MobileNet, ResNet, or EfficientNet
- Increasing the number of training epochs where appropriate
- Deploying the trained model as a web or mobile application

## Conclusion

This project demonstrates the use of Deep Learning and Convolutional Neural Networks for rice leaf disease classification.

The CNN model was trained using image preprocessing and data augmentation techniques and achieved approximately 69.5% validation accuracy after 15 epochs.

The project provides a foundation for developing automated agricultural disease detection systems and can be further improved using transfer learning and additional training data.

## Author

**Bhavani K.**
