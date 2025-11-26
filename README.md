# Face-Mask-Detection

## Face Mask Detection System using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)

A high-performance **Computer Vision system** capable of classifying images as "Masked" or "Unmasked" in real-time. Built using a custom **Convolutional Neural Network (CNN)** architecture and trained on a dataset of ~4000 images, achieving **90%+ accuracy**.

## Key Features

* **End-to-End Pipeline:** Handles the complete workflow including data ingestion, preprocessing (resizing to 128x128, normalization), model training, and final inference.
* **Robust Image Processing:** Implements critical **BGR-to-RGB channel conversion** using OpenCV to ensure the model interprets color channels correctly during real-world predictions.
* **Overfitting Mitigation:** Utilizes **Dropout layers (0.5 rate)** and strategic validation splits to ensure the model generalizes effectively to unseen data.
* **Model Persistence:** Saves trained weights in the **`.keras`** format, allowing for instant loading without the need for retraining.

## Tech Stack 
* Deep Learning Framework: TensorFlow & Keras
* Image Processing: OpenCV (cv2), PIL (Python Imaging Library)
* Data Manipulation: NumPy, Matplotlib
* Model Selection: Scikit-Learn (train_test_split)

## How to Run
* Clone the Repository
* Install Dependencies
 ```bash
  pip install -r requirements.txt
  ```
* Run the main.py file and make sure you have an image ready to test
 ```bash
  python main.py
  ```
* Enter Image Path When prompted
