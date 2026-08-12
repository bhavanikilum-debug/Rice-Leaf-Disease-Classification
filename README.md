# Rice Leaf Disease Classification using CNN

## Project Overview

This project focuses on classifying rice leaf images into three different disease categories using a Convolutional Neural Network (CNN).

The objective is to build an image classification model that can identify the disease affecting a rice leaf based on its visual characteristics.

## Disease Classes

The dataset contains three classes:

- Bacterial leaf blight
- Brown spot
- Leaf smut

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Convolutional Neural Network (CNN)
- Image Data Augmentation

## Project Workflow

1. Load and organize the image dataset
2. Explore the dataset and identify the disease classes
3. Preprocess the images
4. Apply data augmentation
5. Build a CNN model
6. Train the model
7. Evaluate validation performance
8. Add Dropout as a regularization technique
9. Compare the base CNN with the CNN using Dropout
10. Select the more reliable model based on generalization behavior

## CNN Architecture

The CNN uses:

- Convolutional layers for extracting image features
- ReLU activation for non-linearity
- Pooling layers for reducing spatial dimensions
- Dropout for regularization
- Softmax activation in the output layer for multi-class classification

The Adam optimizer was used during model training.

## Data Augmentation

Data augmentation was applied to generate variations of the training images.

This helps the model learn more general image patterns and reduces the possibility of overfitting to the training images.

## Model Comparison

### Base CNN

- Training accuracy: approximately 70%
- Validation accuracy: fluctuated between approximately 56% and 69%
- Showed signs of overfitting
- Learned the training data well but was less stable on unseen validation data

### CNN with Dropout

- Training accuracy: approximately 67%
- Final validation accuracy: 56.52%
- Final validation loss: 0.9994
- Dropout was used as a regularization technique
- Provided more stable generalization behavior
- Did not produce a major improvement in validation accuracy

## Final Observation

Adding Dropout slightly reduced training accuracy but helped address overfitting and improve the model's generalization behavior.

The validation accuracy did not improve significantly, which may be related to the relatively small dataset.

For this experiment, the CNN with Dropout was preferred because of its regularization and more reliable generalization behavior rather than simply selecting the model with the highest training accuracy.

## Conclusion

This project demonstrates how CNNs can be applied to classify rice leaf diseases from images.

The experiment also demonstrates the importance of comparing training and validation performance and using regularization techniques such as Dropout when overfitting is observed.

## Project Type

Deep Learning — Image Classification

## Author

**Bhavani K.**
