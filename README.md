# Parkinson’s Disease Detection using Deep Learning

## Overview
This project focuses on detecting Parkinson’s disease using deep learning techniques. Two different approaches are implemented: a custom Convolutional Neural Network (CNN) and a pretrained ResNet model using transfer learning. The goal is to compare performance and improve classification accuracy on medical data.

## Objectives
- Build a deep learning model for disease detection
- Use transfer learning with a pretrained ResNet model
- Compare performance of a custom CNN and ResNet
- Apply proper data preprocessing and normalization techniques
- Evaluate model performance using standard metrics

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Project Structure
- `custom_cnn.py` – Implementation of a custom CNN model
- `resnet_model.py` – Implementation of pretrained ResNet model
- `README.md` – Project documentation

## Dataset
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set

Note: The dataset is not included in this repository due to size limitations.

## Methodology
- Data preprocessing including normalization of pixel values from 0–255 to 0–1
- Model development using:
  - Custom CNN architecture built from scratch
  - Pretrained ResNet model (transfer learning)
- Fine-tuning of pretrained layers for improved performance
- Training and validation of both models
- Performance evaluation and comparison

## Results
Both models were trained and evaluated on the dataset. The pretrained ResNet model achieved better performance due to its deep architecture and transfer learning capability, while the custom CNN served as a baseline model.

(Add accuracy or evaluation results here if available)

## How to Run
1. Download the dataset from the Kaggle link provided above
2. Install required libraries:
   pip install tensorflow numpy matplotlib
3. Run the model files:
   python custom_cnn.py
   python resnet_model.py

## Future Improvements
- Improve model accuracy through hyperparameter tuning
- Experiment with other pretrained models
- Deploy the model as a web or mobile application

## Author
Divyanjali Khorkar
