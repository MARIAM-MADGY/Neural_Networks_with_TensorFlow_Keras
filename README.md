# Task 3: Neural Networks with TensorFlow/Keras
📌 Description

In this task, I built and trained a simple feed-forward neural network using TensorFlow/Keras to classify images from the MNIST dataset. The goal was to understand the complete workflow of deep learning, starting from data preprocessing to training, evaluation, and hyperparameter tuning.

🎯 Objectives

Load and preprocess the dataset (MNIST digits).

Design a simple feed-forward neural network architecture.

Train the model using backpropagation.

Evaluate the model performance using accuracy and loss curves.

Perform hyperparameter tuning (learning rate, batch size, epochs) to improve performance.

🛠 Tools & Libraries

Python

TensorFlow / Keras

NumPy

Matplotlib

Pandas

🚀 Implementation Steps

Import Libraries → TensorFlow, Keras, Matplotlib, NumPy.

Load Dataset → Used the MNIST dataset (handwritten digits 0–9).

Preprocessing → Normalized pixel values and converted labels to one-hot encoding.

Visualization → Displayed sample digits from the dataset.

Model Design → Created a Sequential Neural Network with Dense and Flatten layers.

Compile Model → Used Adam optimizer and categorical crossentropy as loss.

Train Model → Applied backpropagation with chosen hyperparameters.

Evaluation → Measured test accuracy and loss using model.evaluate.


📊 Results

The neural network achieved high accuracy on the MNIST test set.

Training and validation curves confirmed that the model learned effectively.

Hyperparameter tuning showed the effect of batch size, learning rate, and number of epochs on accuracy and loss.

✅ Conclusion

This task provided practical experience in building a neural network with TensorFlow/Keras, training it on image data, evaluating performance, and improving results through hyperparameter tuning.

Performance Curves → Plotted training & validation accuracy and loss.

Hyperparameter Tuning → Tested different values of learning rate, batch size, and epochs to compare performance.
