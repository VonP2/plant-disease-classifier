# plant-disease-classifier
A classifier for plant leaf diseases using Transfer Learning with ResNet18

## Description
This project uses a pre-trained ResNet18 model with fine-tuning to classify images of plant leaves into 15 different disease categories (e.g., Tomato___Late_blight, Apple___Black_rot, etc.).

The model was trained on the PlantVillage dataset and achieved 88% accuracy on the test set.

## Technologies Used
Python

PyTorch

Torchvision

Google Colab

Matplotlib

Kaggle Datasets

## Project Structure
plant_disease_classifier.ipynb: Model training, saving and test.

README.md: This file.

## Results
Test accuracy: 88%

Model architecture: ResNet18

Dataset: 15 classes, ~50,000 images

## How to Use
Upload an image of a healthy or diseased plant leaf.

The model will classify it into one of the 15 dataset categories.

View the prediction and associated probability.

## Possible Improvements
Add a web interface using Streamlit

Train on the extended dataset (39 classes)

Add per-class metrics and a confusion matrix

## License
For educational purposes only. Dataset provided by the original authors on Kaggle.
