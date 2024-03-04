# Skincancer-Detection
# Overview
This project aims to develop a skin cancer detection system using Convolutional Neural Networks (CNN) deployed on Microsoft Fabric. Skin cancer is one of the most common types of cancer worldwide, and early detection plays a crucial role in improving patient outcomes. By leveraging deep learning techniques, this project seeks to provide a scalable and efficient solution for automated skin cancer detection.
# Features
Convolutional Neural Network (CNN): Utilizes deep learning techniques to analyze skin lesion images for the presence of cancerous cells.
Microsoft Fabric: Deploys the CNN model on Microsoft Fabric, allowing for efficient scaling and management of computational resources.
# Requirements \
Python 3.x TensorFlow Keras Matplotlib NumPy Installation Clone the repository: Install dependencies: Usage Organize your dataset: Place your training images in /lakehouse/default/Files/Train directory. Place your test images in /lakehouse/default/Files/test directory. Run the training script:
This will train the CNN model using the provided dataset. Evaluate the model:
This will evaluate the trained model on the test dataset. Make predictions:
This will make predictions on sample images from the test dataset and display the results. File Structure Notebook.py: Script to train the CNN model and inferencing.
README.md: Project documentation.
Usage Upload skin lesion images using the web interface.
Wait for the system to process the images and provide predictions.
Review the predictions to determine the likelihood of skin cancer.
Contributing Contributions are welcome! Please follow the guidelines outlined in CONTRIBUTING.md.
License This project is licensed under the MIT License - see the LICENSE.md file for details.
