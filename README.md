
# Digits Collection Dataset  

This repository contains a dataset of handwritten digits collected from **28 university students at ENSIA (École Nationale Supérieure de l'Intelligence Artificielle), Algeria**. The dataset is designed for machine learning tasks such as digit classification and recognition, similar to the MNIST dataset.  

## Dataset Overview  

The dataset is stored in a CSV file located in the `data` directory under the name **`data.csv`**. It consists of over **49,000 grayscale images** of handwritten digits (0-9). Each image is represented as a **flattened vector of pixel values**, with each pixel stored as a separate column. Additionally, a **label column** is provided to indicate the corresponding digit (class).  

## Structure  

- **Images**: Each row in the dataset corresponds to a single digit image, with pixel intensity values stored as numerical features.  
- **Labels**: The dataset includes a dedicated column for digit labels (0-9), indicating the ground truth for each image.  
- **Format**: The dataset is saved as a CSV file for easy integration with machine learning frameworks.  

This dataset can be used for training and evaluating machine learning models, including deep learning architectures for digit classification.  
