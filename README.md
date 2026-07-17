# CNN for MNIST Handwritten Digit Classification

## Overview

This project implements a Convolutional Neural Network (CNN) using **PyTorch** to classify handwritten digits from the **MNIST** dataset.

The model is trained on 60,000 handwritten digit images and evaluated on 10,000 test images. It demonstrates the complete deep learning workflow, including data preprocessing, CNN architecture design, model training, validation, saving the best model, and prediction.

---

## Features

* Load the MNIST dataset using Torchvision
* Image preprocessing with normalization
* Custom CNN architecture
* Train using Adam optimizer
* CrossEntropyLoss for multi-class classification
* Save the best-performing model
* Evaluate test accuracy
* Predict handwritten digits
* Visualize sample images with labels

---

## Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib

---

## Project Structure

```text
CNN_For_MNIST.ipynb
Best Model.pt
README.md
```

---

## CNN Architecture

* Convolution Layers
* ReLU Activation
* Max Pooling
* Fully Connected Layers
* Softmax via CrossEntropyLoss

---

## Training Configuration

* Dataset: MNIST
* Batch Size: 64
* Optimizer: Adam
* Loss Function: CrossEntropyLoss
* Epochs: 10

---

## Dataset

The project uses the MNIST handwritten digit dataset.

* Training Images: 60,000
* Test Images: 10,000
* Image Size: 28 × 28
* Classes: 10 (Digits 0–9)

---

## Results

The trained CNN successfully classifies handwritten digits with high accuracy on the MNIST test dataset.

The notebook also demonstrates:

* Model training
* Validation
* Model saving
* Prediction
* Image visualization

---

## Future Improvements

* Add dropout layers
* Hyperparameter tuning
* Data augmentation
* TensorBoard integration
* Deploy using Streamlit or Flask

---

## How to Run

1. Clone the repository

```bash
https://github.com/Sujan-Adhikari875/CNN-for-MNIST-Handwritten-Digit-Classification.git
```

2. Install dependencies

```bash
pip install torch torchvision matplotlib numpy
```

3. Run the notebook

```bash
jupyter notebook CNN_For_MNIST.ipynb
```

---

## Author

ADHIKARI SUJAN

