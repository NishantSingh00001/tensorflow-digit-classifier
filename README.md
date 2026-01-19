# TensorFlow Digit Classifier 🧠🔢

A Deep Learning project that identifies handwritten digits using a Convolutional Neural Network (CNN) architecture built with **TensorFlow** and **Keras**.

## 🚀 Overview
This project uses the classic MNIST dataset to train a neural network to recognize digits (0-9). It serves as a foundational project in Computer Vision and Deep Learning.

## 🛠️ Tech Stack
* **Language:** Python
* **Library:** TensorFlow / Keras
* **Data:** MNIST Dataset
* **Environment:** Google Colab

## 📊 Performance
* **Training Accuracy:** ~98%
* **Test Accuracy:** ~97.5%
* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy

## 📁 Project Structure
* `train_model.ipynb`: The Google Colab notebook containing the training logic.
* `digit_model.h5`: The saved, trained model ready for deployment.

## 💡 Key Learnings
- Normalizing image data for faster neural network convergence.
- Implementing Dropout layers to reduce overfitting.
- Saving and exporting models for future inference (API/Web use).
