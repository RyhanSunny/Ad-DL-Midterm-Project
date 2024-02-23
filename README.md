
# Advanced Deep Learning Project: Optimizer Comparison and Analysis

## Project Overview
This project delves into three state-of-the-art optimizer algorithms: Adagrad, Adam, and RMSprop. By applying these optimizers to an Artificial Neural Network (ANN) model trained on the Fashion MNIST dataset, we aim to uncover the intricacies, advantages, and drawbacks of each method.

## Dataset
The Fashion MNIST dataset comprises 70,000 grayscale images of 10 fashion categories, split into a training set of 60,000 images and a test set of 10,000 images.

## Deep Learning Model - ANN
Our model is designed to classify images into one of the ten categories accurately. It features a sequential architecture with densely connected layers, employing ReLU and Softmax activation functions, BatchNormalization, and Dropout for regularization.

## Setup Instructions
1. **Environment Setup:** Install Python 3.x and create a virtual environment for project dependencies.
2. **Install Dependencies:** Run `pip install -r requirements.txt` to install necessary libraries such as TensorFlow, Keras, Numpy, and Matplotlib.
3. **Download Dataset:** The Fashion MNIST dataset is accessible via TensorFlow/Keras. Our notebooks automatically handle its loading and preprocessing.

## Usage Guide
### General Workflow
1. **Open the Desired Notebook:** Start with the optimizer-specific notebook (`fashion_mnist_<OptimizerName>_optimizer.ipynb`) of your choice.
2. **Follow Markdown Instructions:** Each notebook contains markdown cells providing step-by-step instructions for executing the code cells.
3. **Run Code Cells:** Sequentially execute the code cells to train the ANN model using the selected optimizer, evaluate its performance, and visualize results.

### Specific Notebook Guides
- **Adagrad, Adam, and RMSprop Notebooks:** These notebooks detail the setup, training, and evaluation process for each optimizer. They include code for model definition, compilation, training, and performance metrics visualization.
- **Baseline Model Notebook:** `fashion_mnist_without_optimizer.ipynb` serves as a control experiment to assess the effectiveness of optimizer algorithms.
- **Model and Optimizer Setup:** The `fashionmnist_model_optimizer.ipynb` notebook outlines the generic model architecture and training framework, adaptable to different optimizers.
- **Best Optimizer and Hyperparameter Tuning:** `fashion-mnist-best-optimizer-and-hyperparameter.ipynb` focuses on selecting the optimal optimizer and fine-tuning model hyperparameters for enhanced performance.
- **Results Summary:** The `Results.ipynb` notebook compiles and compares the outcomes of different optimizer trials, guiding the final selection process.

## Files Description
- **Notebooks:** Detailed experiments with specific optimizers, a baseline comparison, optimizer selection, and results summary.
- **Python Scripts:** Modular code for model definition, training, and evaluation (refer to `fashionmnist_model_optimizer.py` for implementation details).

## Acknowledgments
This project is a collaborative effort for the Advanced Deep Learning course's midterm assessment. We thank all contributors for their dedication and insights.
Credit: Noah Nsimbe, Ryhan Sunny, Amaka Genevieve Jane Awa, and Oluwadamilare Matthew Kolawole  
AI and Machine Learning Graduate Program # Class: Advaned Deep Learning  
Humber International Graduate School, Toronto
