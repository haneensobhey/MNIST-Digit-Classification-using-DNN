# MNIST-Digit-Classification-using-DNN
# MNIST Handwritten Digit Classification using Deep Neural Networks

## Project Overview
This project uses a Deep Neural Network (DNN) to classify handwritten digits from 0 to 9 using the MNIST dataset.

## Dataset
The MNIST dataset contains grayscale images of handwritten digits, each with a size of 28 × 28 pixels.

## Model Architecture
- Input layer: 784 features
- Hidden layers: Fully connected Dense layers with ReLU activation
- Output layer: 10 neurons with Softmax activation

## Data Preprocessing
- Flattening images from 28 × 28 pixels into 784 features
- Normalizing pixel values to the range [0, 1]
- Encoding target labels for multiclass classification

## Results
- Training Accuracy: 100%
- Validation Accuracy: 98.37%
- Test Accuracy: 98.28%

## Evaluation
The model is evaluated using accuracy and a confusion matrix to analyze classification errors across the ten digit classes.

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Install the required dependencies.
2. Open `DNN.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook cells in order.

## Learning Outcomes
- Building a Deep Neural Network for multiclass classification
- Data preprocessing and normalization
- Model training and evaluation
- Analyzing classification performance
