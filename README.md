### 100DaysofML-Day5

# Neural Network with TensorFlow & Keras

This project demonstrates how to build a simple feedforward neural network using TensorFlow and Keras for the Pima Indians Diabetes dataset.

### Overview

The Pima Indians Diabetes dataset is a collection of medical records of Pima Indians and whether they had an onset of diabetes within five years. It's a widely-used dataset in the field of machine learning for binary classification problems. The dataset contains 768 instances and 9 attributes, including the target variable (whether the patient has diabetes or not).

### Getting Started

To run this project, you need to have the following prerequisites installed on your machine:

- Python 3.x
- TensorFlow
- Keras

### You can install TensorFlow and Keras using pip:

    pip install tensorflow
    pip install keras

### How to Run

- Clone this repository.
- Navigate to the project directory.
- Run the script with the following command:

      python simple_neural_network_keras.py

### Project Structure

- simple_neural_network_keras.py: The main Python script that trains and evaluates the neural network model.

### Model

The neural network model is built using the Keras Sequential API. It consists of one hidden layer with 12 neurons and an output layer with one neuron for binary classification. The model uses the 'relu' activation function for the hidden layer and the 'sigmoid' activation function for the output layer. The model is compiled with the 'binary_crossentropy' loss function and the 'adam' optimizer.

### Evaluation

The model is evaluated using the k-fold cross-validation technique with 10 folds. The accuracy metric is used to assess the model's performance.

### Acknowledgments

This project was inspired by Jason Brownlee, PhD at [Machine Learning Mastery](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/).
