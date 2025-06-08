# Gender Classification using Convolutional Neural Network (CNN)

This project aims to classify gender (male/female) based on facial image data using a custom-built Convolutional Neural Network (CNN) architecture with hyperparameter tuning.

## Model
The model is built using:
- TensorFlow & Keras (CNN architecture)
- Keras Tuner (RandomSearch) for hyperparameter tuning
- Optimizer: Adam
- Binary classification with Sigmoid activation

## Performance
- Accuracy: 96% on test data
- F1-Score: 0.96 for both Male and Female
- Evaluated using confusion matrix, classification report, and visual sample predictions.

## Dataset
- Source: [Kaggle – Gender Classification Dataset](https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset)
- Composed of pre-cropped facial images labeled as Male or Female.
- Image size resized to (32, 32, 3)
- Training/Validation/Test split: 80/20

## Project Highlights
- Image preprocessing with `ImageDataGenerator` (including rescaling and augmentation)
- Dynamic architecture configuration via Keras Tuner
- Visual analysis of training loss/accuracy and confusion matrix
- Implemented in a clean and modular notebook

##  How to Run

```bash
# (optional) create and activate virtual environment
pip install -r requirements.txt
# open the notebook
jupyter notebook 30_Fakhri_Rayhan_Alaudin_Program_Project_DIP.ipynb
