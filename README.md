# Digit Recogniser

This project is a machine learning application for recognizing handwritten digits using the MNIST dataset. The model, built with TensorFlow and trained on a GPU using TensorFlow Metal, achieves high accuracy in classifying digits from 0 to 9. The implementation involves data preprocessing, model training, and prediction on real handwritten digit images.

The goal of this project is to create a model that can accurately classify handwritten digits (0-9). The MNIST dataset, a large database of handwritten digits commonly used for training various image processing systems, is used for training and testing the model.

# Dataset

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits, each of which is 28x28 pixels.

# Model Training

We used only the training images from the MNIST dataset to train our model. The data was split into training and testing sets using an 80-20 train-test split. This means 48,000 images were used for training, and 12,000 images were used for validation.

The model was trained on TensorFlow with Metal, enabling GPU-accelerated learning. This significantly improved the training speed and efficiency.

# Predictions

The trained model was used to make predictions on real handwritten digits. These handwritten digits were provided as input images, and the model successfully classified them with high accuracy.

# Model Architecture

The model is built using a simple feedforward neural network with the following layers:

Input layer: 784 neurons (28x28 pixels)
Hidden layer: 128 neurons, ReLU activation
Output layer: 10 neurons (one for each digit), Softmax activation
Results

The model achieves a high accuracy on the test dataset. Detailed performance metrics and visualizations of the results can be found in the Jupyter notebook.

