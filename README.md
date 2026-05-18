# Intel Image Classification using CNN 🏔️

A Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify natural scene images into 6 categories.

## 📊 Results
- **Test Accuracy:** ~80%
- **Dataset:** 14,000+ training images, 3,000 test images

## 🏷️ Classes
| Class | Description |
|---|---|
| Buildings | Urban structures |
| Forest | Dense tree coverage |
| Glacier | Ice and snow landscapes |
| Mountain | Mountain terrain |
| Sea | Ocean and water bodies |
| Street | Urban roads and paths |

## 🧠 Model Architecture
- 3 Convolutional blocks with BatchNormalization and MaxPooling
- Dropout (0.5) to prevent overfitting
- Dense output layer with Softmax activation

## 📦 Dataset
[Intel Image Classification — Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Run Cell 1 to install dependencies
3. Run Cell 2 to import libraries
4. The dataset will be downloaded automatically via `kagglehub`
5. Run remaining cells in order

## 🛠️ Dependencies
- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn
- kagglehub
