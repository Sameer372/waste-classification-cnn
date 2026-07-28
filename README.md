# Waste Classification Using CNN

This project implements a **Convolutional Neural Network (CNN)** model for automatic waste image classification. The model is trained to classify waste images into two categories: **Organic Waste** and **Recyclable Waste**.

The project demonstrates the application of deep learning techniques for automated waste management systems.

---

## Dataset

**Dataset Name:** Mendeley Waste Classification Dataset

**Dataset Source:**  
Mendeley Data  
https://data.mendeley.com/datasets/n3gtgm9jxj/3

The dataset contains waste images divided into two classes:

- Organic Waste
- Recyclable Waste

The dataset is used for training and evaluating the CNN-based classification model.

---

## Project Objective

The main objective of this project is to develop a CNN model that can automatically identify and classify waste images into their respective categories.

---

## Model Architecture

A basic CNN model was developed using **TensorFlow and Keras**.

The model includes:

- Convolutional layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Dense layers for classification
- Dropout layer to reduce overfitting
- Sigmoid activation for binary classification

---

## Data Preprocessing and Augmentation

Before training, images were processed using:

- Image resizing
- Pixel normalization
- Data augmentation techniques

Data augmentation was applied to improve model generalization and reduce overfitting.

---

## Overfitting Control

To prevent overfitting:

- Dropout regularization was applied
- Training and validation performance were monitored using accuracy and loss curves

---

## Training Details

- **Framework:** TensorFlow / Keras
- **Model Type:** Convolutional Neural Network (CNN)
- **Number of Classes:** 2
- **Epochs:** 10
- **Learning Rate:** Fixed Learning Rate

---

## Results

The trained CNN model achieved the following performance:

- **Validation Accuracy:** 87.41%
- **Best Validation Loss:** 0.3094

The model successfully classifies waste images into Organic and Recyclable categories.

---

## Performance Analysis

The model performance was evaluated using:

- Training and validation accuracy curves
- Training and validation loss curves
- Classification results
- Confusion matrix analysis

These evaluations demonstrate that the model can effectively distinguish between different waste categories.

---

## Conclusion

This project successfully developed a CNN-based waste classification system using deep learning techniques.

The model shows the potential of computer vision and deep learning approaches for automated waste management applications.

Future improvements can include:
- Increasing dataset size
- Applying advanced augmentation techniques
- Using transfer learning models for higher accuracy

---

## Technologies Used

- Python
- TensorFlow
- Keras
- CNN
- Google/Kaggle GPU
- Jupyter Notebook
