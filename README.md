# Deep Learning – Fashion Image Classification

## Project Overview

This project demonstrates how **Deep Learning** can be used to automatically classify fashion product images into different categories.

The project is designed as a Google Colab practical for **BBA AI/ML students** and uses the **Fashion MNIST** dataset. The model takes a fashion product image as input and predicts its product category.

## Business Problem

In an e-commerce company, thousands of product images may need to be categorized before products are added to a website.

Manual classification can be repetitive and time-consuming. A Deep Learning model can assist employees by automatically predicting the category of a product from its image.

### Example

**Input:** Fashion product image
**Output:** Predicted product category

## Product Categories

The model classifies images into 10 categories:

1. T-shirt / Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## Dataset

The project uses the **Fashion MNIST** dataset.

The dataset contains grayscale images of fashion products. It is downloaded automatically through TensorFlow/Keras, so no manual dataset upload is required.

Each image is processed so that pixel values are converted from **0–255 to 0–1**, making the data easier for the neural network to process.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab
* Fashion MNIST

## Model Architecture

A simple Artificial Neural Network is used:

```text
Input Image
     ↓
Flatten Layer
```
