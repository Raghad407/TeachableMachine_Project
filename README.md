# TeachableMachine_Project
Image recognition project using Teachable Machine and Python
Image Recognition Project Using Teachable Machine
1. Project Description
This project is an image recognition model created using Google Teachable Machine. The model was trained to classify images into two classes: Cat and Dog.
2. Creating the Model
Opened Google Teachable Machine.
Selected Image Project.
Created two classes:
Class 1: Cat
Class 2: Dog
Added images of cats to the Cat class.
Added images of dogs to the Dog class.
3. Training the Model
The model was trained using the collected images for both classes. After training, the model was tested using new images to check its prediction accuracy.
4. Model Evaluation
The trained model was evaluated by using test images that were not part of the training images. The model successfully predicted the class of the input images as either Cat or Dog.
A screenshot of the prediction result is included in this repository.
5. Exporting the Model
After training and evaluation, the model was exported from Teachable Machine using:
TensorFlow → Keras
The exported model files are included in this repository.
6. Python Prediction Script
A Python script named predict.py was created to:
Load the trained Keras model.
Load the class labels.
Accept an input image.
Resize and prepare the image.
Predict whether the image belongs to the Cat or Dog class.
Display the predicted class and confidence percentage.
7. Files Included
predict.py — Python script used for image prediction.
keras_model.h5 — Trained Keras model.
labels.txt — Class labels.
output.png — Screenshot of the prediction output.
README.md — Project documentation.
8. Result
The Python script successfully loaded the trained model and predicted the class of the input image. The prediction result and confidence percentage are shown in the submitted screenshot.
