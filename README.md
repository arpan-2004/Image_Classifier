Predict whether a person looks happy or sad from an image using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

✨ Features

Simple CNN (3× Conv + MaxPool → Dense) for binary classification

Train/Val split via image_dataset_from_directory

Optional data augmentation

Evaluation metrics + confusion matrix

Single-image inference script (OpenCV)

This project is a deep learning–based image classifier that can automatically detect whether a person appears happy or sad in a given image. The model is built using TensorFlow/Keras with a Convolutional Neural Network (CNN) architecture, which is well-suited for extracting visual features from images.

The dataset consists of two categories — Happy and Sad people — organized in separate folders. Images are preprocessed, resized, and fed into the CNN for training. The model learns to distinguish facial expressions by identifying unique patterns and features such as smiles, frowns, and other visual cues.

This project also integrates OpenCV for handling input images and supports custom predictions, allowing you to test with your own images. The system can be extended further to include more emotion classes (like anger, surprise, neutral, etc.) for a richer emotion detection model.

The primary goal of this project is to demonstrate how deep learning can be applied to emotion detection, which has real-world applications in mental health monitoring, customer experience analysis, human-computer interaction, and AI-driven emotion recognition systems.
