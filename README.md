# ✍️ Handwritten Digit Identification

A deep learning project that identifies handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The model achieves high accuracy and is designed for real-time prediction on grayscale images.

## 📌 Project Overview

This project demonstrates how to build and train a CNN to classify handwritten digits using:
- TensorFlow and Keras
- MNIST dataset (60,000 training + 10,000 test images)
- Image normalization and reshaping
- Dropout regularization for better generalization

## 🧠 Techniques Used

- **CNN Architecture**: Conv2D → MaxPooling → Flatten → Dense → Dropout → Output
- **Activation Functions**: ReLU and Softmax
- **Loss Function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam
- **Evaluation Metrics**: Accuracy

## 📊 Results

- Achieved **98.45% test accuracy** after 5 epochs
- Model saved as `Digit.keras` for future deployment
- Real-time prediction capability with confidence scores

## 📁 Files Included

- `Identifying Digit with images.ipynb`: Jupyter Notebook with full implementation
- `Digit.keras`: Trained model file
- `README.md`: Project documentation

## Feel free to fork, star, or contribute!
