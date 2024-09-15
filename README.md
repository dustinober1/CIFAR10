# CIFAR10

This repository contains a project focused on building and training a deep learning model on the CIFAR-10 dataset, a popular dataset for image classification tasks.

## Table of Contents

- [Overview](#overview)
- [Files](#files)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Contributing](#contributing)
- [License](#license)

## Overview

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. This project involves building a Convolutional Neural Network (CNN) model using Python and popular deep learning libraries to classify these images. The repository includes a Jupyter Notebook that contains the full code for loading the dataset, preprocessing the data, building the model, training, and evaluating the model.

## Files

- **CIFAR10.ipynb**: Jupyter Notebook containing the code to build, train, and evaluate the CNN model on the CIFAR-10 dataset.
- **cifar10_51.pth, cifar10_63.pth, cifar10_68.pth, cifar10_82.pth, cifar10_95.pth**: Model checkpoint files saved at different training stages.
- **cifar10_model.h5**: Saved model in HDF5 format.

## Installation

To run the code in this repository, you need to have Python and the required libraries installed.

1. **Clone the repository**:

    ```bash
    git clone https://github.com/dustinober1/CIFAR10.git
    cd CIFAR10
    ```

2. **Install the required dependencies**:

    You can install the necessary Python libraries using pip:

    ```bash
    pip install numpy pandas tensorflow keras matplotlib
    ```

## Usage

To run the Jupyter Notebook and train the model on the CIFAR-10 dataset:

1. Open the `CIFAR10.ipynb` file in Jupyter Notebook or JupyterLab.

2. Run the cells step-by-step to load the data, preprocess it, build the model, train it, and evaluate its performance.

3. You can also use the pre-trained model weights provided in the `.pth` and `.h5` files to load and test the models directly without retraining.

## Models

- **cifar10_51.pth, cifar10_63.pth, cifar10_68.pth, cifar10_82.pth, cifar10_95.pth**: These files are PyTorch model checkpoints saved at different epochs during training. You can load these checkpoints to continue training or evaluate the model's performance at specific epochs.
- **cifar10_model.h5**: This file is the final saved Keras model that can be loaded and used for prediction or fine-tuning.

## Contributing

Contributions are welcome! If you have ideas for improving the model, adding new features, or any other suggestions, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
