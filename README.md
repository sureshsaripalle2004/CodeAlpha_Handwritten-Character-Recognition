# CodeAlpha – Handwritten Character Recognition

A Convolutional Neural Network (CNN) based handwritten digit recognition system developed as part of the CodeAlpha Machine Learning Internship.

The project uses the MNIST handwritten digit dataset to train a deep learning model capable of recognizing handwritten digits from 0 to 9.

---

##  Project Overview

Handwritten character recognition is an important application of computer vision and machine learning. It enables computers to interpret handwritten characters and convert them into machine-readable information.

In this project, a Convolutional Neural Network (CNN) is developed using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

The project includes:

- MNIST dataset loading and exploration
- Image preprocessing
- CNN model development
- Model training and validation
- Performance evaluation
- Confusion matrix analysis
- Classification report
- Sample digit predictions
- Real-world handwritten digit testing
- Training and validation performance visualization
- Saving model evaluation results

---

## Objectives

The main objectives of this project are:

1. To understand the MNIST handwritten digit dataset.
2. To preprocess handwritten digit images for CNN input.
3. To develop a CNN-based image classification model.
4. To train the model using the MNIST training dataset.
5. To evaluate the model using the test dataset.
6. To analyze model performance using accuracy, precision, recall, and F1-score.
7. To visualize the confusion matrix and training performance.
8. To test the trained model on a real-world handwritten digit image.

---

## Dataset

### MNIST Handwritten Digit Dataset

The MNIST dataset contains grayscale images of handwritten digits ranging from **0 to 9**.

### Dataset Characteristics

- Training images: 60,000
- Test images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10
- Classes: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- Image type: Grayscale

The dataset is loaded directly using the TensorFlow/Keras built-in MNIST dataset.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

---

## Model Architecture

A Convolutional Neural Network (CNN) is used for handwritten digit classification.

### CNN Architecture

```text
Input Image
    ↓
28 × 28 × 1
    ↓
Conv2D – 32 Filters
    ↓
MaxPooling2D
    ↓
Conv2D – 64 Filters
    ↓
MaxPooling2D
    ↓
Flatten
    ↓
Dense – 128 Neurons
    ↓
Dropout – 30%
    ↓
Dense – 10 Neurons
    ↓
Softmax
    ↓
Predicted Digit (0–9)
