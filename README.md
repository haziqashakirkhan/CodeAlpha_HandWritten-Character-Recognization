#  Handwritten Character Recognition using CNN

A Deep Learning project that recognizes handwritten digits (0–9) using the **MNIST dataset** and a **Convolutional Neural Network (CNN)** built with TensorFlow and Keras.

---

##  Project Overview

This project demonstrates how deep learning can be used for image classification. The model is trained on the MNIST dataset containing 70,000 handwritten digit images and learns to classify unseen images with high accuracy.

The system uses a CNN architecture that extracts features from images and predicts the correct digit label.

---

##  Objective

To build a machine learning model that can:
- Recognize handwritten digits (0–9)
- Achieve high accuracy using CNN
- Generalize well on unseen test data

---

##  Dataset

- **Dataset:** MNIST
- **Total Images:** 70,000
  - Training: 60,000 images
  - Testing: 10,000 images
- **Image Size:** 28x28 pixels (grayscale)
- **Classes:** 10 (digits 0–9)

---

## Model Architecture

The CNN model consists of:

- Convolutional Layers (feature extraction)
- MaxPooling Layers (dimensionality reduction)
- Flatten Layer
- Dense Fully Connected Layers
- Dropout Layer (to reduce overfitting)
- Softmax Output Layer (classification)

---

##  Technologies Used

- Python 
- TensorFlow 
- Keras
- NumPy
- Matplotlib 

---

##  How It Works

1. Load MNIST dataset
2. Normalize pixel values (0–1 range)
3. Reshape images for CNN input
4. Build CNN model
5. Train model on training data
6. Evaluate performance on test data
7. Make predictions on new images
8. Visualize results using Matplotlib

---

##  Results

- Achieved **~97%–99% accuracy** on MNIST dataset
- Model successfully classifies handwritten digits
- Strong performance on unseen test data

---

##  Sample Prediction

The model predicts the digit from an image and displays it using Matplotlib:
Predicted: 7


---

##  Future Improvements

- Extend to **EMNIST dataset (A–Z letters)**
- Build real-time handwriting recognition app
- Deploy using **Streamlit or Flask**
- Upgrade to **CRNN (CNN + RNN)** for word recognition

---

##  Project Structure
MNIST-Project/
            │
            ├── model.py
            ├── train.py
            ├── test.py
            ├── requirements.
            ├── README.md
            └── dataset (auto-downloaded)

---

##  Author

Developed as part of an AI/ML Internship Project focused on deep learning and image classification.

---

##  If you like this project

Feel free to:
- Star ⭐ the repository
- Fork it 
- Improve it 
