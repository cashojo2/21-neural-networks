# 21-neural-networks

This repository demonstrates the use of scikit-learn and TensorFlow to implement a binary classification model designed to assist a nonprofit foundation in identifying which applicants to fund based on their likelihood of success. The dataset consists of over 34,000 funding organizations and 12 features.

First, the data was preprocessed to ensure suitability for the neural network model. To reduce noise, binning techniques were applied to features with a large number of unique values, consolidating rare values into an "Other" category. One-hot encoding was utilized to enable the model to effectively interpret categorical data. The data was then normalized using StandardScaler to ensure optimal performance during training.

An instance of the neural network model was defined and trained using TensorFlow. The model's accuracy was optimized by adjusting the hyperparameters. Various configurations for the number of layers, nodes per layer, number of epochs, and activation functions were experimented with. Ultimately, the final model included two hidden layers with ReLU activation functions, comprising 50 and 20 nodes, respectively, along with an output layer utilizing a sigmoid activation function. This configuration achieved an accuracy of 72.8% while effectively minimizing loss.
