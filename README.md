# TB Detection Website

This project is a web application for detecting Tuberculosis (TB) using a deep learning model, specifically the ResNet50 architecture. The application allows users to upload chest X-ray images and receive predictions on the presence of TB.

## Usage

1. Open the web application in your browser.
2. Click on the "Upload Image" button to upload a chest X-ray image.
3. After the image is processed, the model will return a prediction indicating whether TB is detected or not.

## Model Training

The TB detection model is built using the ResNet50 architecture. Here’s a brief overview of the training process:

1. **Dataset**: The model is trained on a dataset of chest X-ray images labeled as either 'TB' or 'Normal'.
2. **Preprocessing**: Images are resized and normalized before feeding them into the model.
3. **Training**: The model is trained using TensorFlow and Keras with appropriate loss functions and optimizers.
4. **Evaluation**: The model is evaluated based on accuracy and other metrics on a validation set.
