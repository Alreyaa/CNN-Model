# ASL Classification using CNN

**American Sign Language Classification using Convolutional Neural Network (CNN)**


## 🧠 Introduction

This project implements a **Convolutional Neural Network (CNN)** to recognize and classify hand gestures representing the American Sign Language (ASL) alphabet. It is a supervised image classification task using deep learning techniques.


## 🗂️ Dataset Used

**Dataset Name**: American Sign Language (ASL) Alphabet

- **Description**: The dataset contains images of hand signs corresponding to the 26 letters of the English alphabet (A–Z).
- **Image Size**: Typically 64x64 or 200x200
- **Color Mode**: RGB
- **Classes**: 26 (A–Z)


## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn


## ⚙️ Model Architecture

The model follows a typical CNN structure:
- Convolutional Layers with ReLU activation
- MaxPooling Layers
- Flatten Layer
- Dense (Fully Connected) Layers
- Softmax Output Layer for multi-class classification


## 🔄 Workflow

1. **Data Loading**
 - Images are loaded from the ASL dataset directory.
 - Labels are automatically assigned based on folder names.

2. **Preprocessing**
 - Images are resized.
 - Normalized to [0, 1] range using `rescale=1./255`.
 - Split into training and validation sets.

3. **Model Building**
 - CNN architecture with Conv2D, MaxPooling, Flatten, Dense layers.

4. **Training**
 - Model is trained on training data with validation tracking.

5. **Evaluation**
 - Accuracy and loss plots
 - Confusion matrix and performance report


## 📊 Evaluation Metrics

- Accuracy
- Loss
- Confusion Matrix
- Classification Report


## ▶️ How to Run

1. Download the ASL Alphabet dataset from Kaggle.
2. Place it in the correct folder structure (`asl_dataset/`).
3. Install required libraries:
 ```bash
 pip install tensorflow numpy pandas matplotlib seaborn scikit-learn

