# Image Classification with TensorFlow

This project is a comprehensive implementation of an image classification system using TensorFlow and Keras. It demonstrates how to process raw image data, design a Convolutional Neural Network (CNN), and train it to classify images into specific categories. The project covers end-to-end implementation, including data preprocessing, model evaluation, and real-time predictions. 

The goal is to provide a clear, practical example of building an image classification pipeline that can handle real-world datasets organized in directories.

---

## Features
- **Data Handling**: Efficiently load and preprocess image data from directories, ensuring the dataset is ready for model training.
- **Model Architecture**: Design a CNN model using TensorFlow and Keras, leveraging layers such as convolutional, max-pooling, batch normalization, and dropout for enhanced learning.
- **Training and Validation**: Train the model on a labeled dataset while tracking its performance with accuracy and loss metrics to avoid overfitting.
- **Evaluation**: Use the test set to evaluate the model's ability to generalize to unseen data.
- **Visualization**: Visualize key metrics like accuracy and loss trends over epochs to understand model performance. Display sample predictions with their confidence levels.
- **Custom Predictions**: Provide an easy-to-use function to predict the category of new images, outputting both the predicted class and its confidence score.

---

## Requirements
To successfully run the project, you need the following:

### Software
- **Python**: Version 3.7 or higher.

### Libraries
- **TensorFlow**: For deep learning model development.
- **Keras**: High-level API integrated with TensorFlow for building neural networks.
- **NumPy**: For numerical operations and array handling.
- **Matplotlib**: For plotting training performance and visualizing predictions.
- **scikit-learn**: For preprocessing data and performance evaluation metrics.

### Installation
Install the required libraries with the following command:
```bash
pip install tensorflow keras numpy matplotlib scikit-learn
