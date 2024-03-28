# Digit Recognition Project

## Overview

This project is a machine learning model that recognizes digits from images. It uses the MNIST dataset, which is a large database of handwritten digits that is commonly used for training various image processing systems. The model is built using PyTorch, a popular deep learning library.

## Features

- Utilizes the MNIST dataset for training and testing.
- Implements a Convolutional Neural Network (CNN) for image recognition.
- Provides training and testing data loaders.
- Includes a model training process with output logging.
- Evaluates the model on test data and reports accuracy.

## Requirements

To run this project, you will need:

- Python 3.6 or higher
- PyTorch
- torchvision
- matplotlib (for displaying images)

## Quick Start

To quickly clone and run this project, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone <your-repository-url>
    cd <repository-name>
    ```

2. **Create a Virtual Environment (Optional)**

    It's a good practice to create a virtual environment for Python projects. This step is optional but recommended.

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install Dependencies**

    Install the required Python packages using pip:

    ```bash
    pip install torch torchvision matplotlib
    ```

4. **Run the Application**

    Start the training and evaluation process by running the main script:

    ```bash
    python <your-script-name>.py
    ```

    This will begin the training process, and after training, the model's accuracy on the test set will be displayed. The script also demonstrates a prediction for a digit image from the test dataset.

## Project Structure

- `train_data` & `test_data`: DataLoaders for training and testing sets.
- `CNN`: The CNN model definition.
- `train`: Function to train the model.
- `test`: Function to evaluate the model's accuracy on the test dataset.
- Visualization of prediction results.


## License

This project is licensed under the MIT License.



