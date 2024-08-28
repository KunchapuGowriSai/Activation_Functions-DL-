Activation Function Comparison on CIFAR-10 Dataset
This project compares the performance of different activation functions (Sigmoid, ReLU, ELU, SELU, GELU, and Tanh) on the CIFAR-10 dataset using a simple neural network. The experiment aims to analyze how each activation function impacts the training loss and model weights.

Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 50,000 training images and 10,000 validation images.

Experiment Setup
Models: A simple neural network with two hidden layers, each containing 512 units.
Activation Functions:
Sigmoid
ReLU
ELU
SELU
GELU
Tanh
Optimizer: Stochastic Gradient Descent (SGD)
Loss Function: Categorical Crossentropy
Metrics: Accuracy
Training Parameters:
Epochs: 10
Batch Size: 128
Validation Split: 20%
Files
activation_comparison.py: The Python script containing the experiment code.
README.md: This file, providing an overview of the project and instructions for running the experiment.
How to Run the Experiment
Ensure that the required libraries are installed:
bash
Copy code
pip install numpy pandas matplotlib tensorflow keras
Run the Python script:
bash
Copy code
python activation_comparison.py
Results
The experiment produces a plot showing the loss over epochs for each activation function, helping to compare their performances. Additionally, the maximum weights in each layer for each activation function are printed.

Contact
For any questions or discussions about this project, feel free to reach out via email: kunchapugowrisai143@gmail.com.
