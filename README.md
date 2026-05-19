# Plant Disease Detection Using CNN

This project is a beginner-level deep learning project for plant disease classification using Convolutional Neural Networks (CNN).

## Project Overview

The model was trained on the PlantVillage dataset using TensorFlow and Keras in Google Colab.

The project includes:

* Image preprocessing
* CNN model building
* Label encoding
* One-hot encoding
* Model training and evaluation
* Accuracy and loss visualization

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Model Architecture

The CNN model consists of:

* Conv2D layers
* MaxPooling layers
* Flatten layer
* Dense layers
* Dropout layer

## Current Limitations

This is an initial version of the project and has some limitations:

* The model was trained only on 5 plant disease classes.
* Limited images were used for training (~200 images per class).
* The model may not generalize well to random internet images.
* Frontend deployment is not included yet.

## Classes Used

* Tomato___Late_blight
* Tomato___healthy
* Grape___healthy
* Orange___Haunglongbing_(Citrus_greening)
* Soybean___healthy

## Results

The model achieved around 95–96% validation accuracy on the selected subset of classes.

## Future Improvements

* Train on full PlantVillage dataset
* Use data augmentation
* Improve model generalization
* Use transfer learning (MobileNet, ResNet)
* Build Flask/Streamlit frontend deployment

## Learning Outcomes

This project helped in understanding:

* CNN architecture
* Convolution and pooling
* Overfitting and dropout
* Image preprocessing
* Deep learning workflow
* Model training and evaluation
