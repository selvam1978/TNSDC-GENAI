# Handwritten Digit Recognition using Convolutional Neural Networks

This notebook demonstrates how to train a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0-9).

## Usage

1. Open the notebook in Google Colab.
2. Run each cell sequentially.
3. The model will be trained on the MNIST dataset, and the training progress will be displayed.
4. After training, the model's accuracy will be evaluated on the test dataset.
5. Finally, a plot showing the training and validation accuracy over epochs will be displayed.

## Code Overview

- `import` statements: Import necessary libraries.
- Load the MNIST dataset: Load the dataset using Keras.
- Preprocess the data: Reshape and normalize input images, and one-hot encode target labels.
- Create the model: Define a CNN model architecture using Keras Sequential API.
- Compile the model: Specify the optimizer, loss function, and evaluation metrics for training.
- Train the model: Fit the model to the training data.
- Evaluate the model: Evaluate the trained model on the test data.
- Plot training history: Visualize the training and validation accuracy over epochs.

## Dependencies

- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
