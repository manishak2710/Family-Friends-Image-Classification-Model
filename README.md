# Family-Friends-Image-Classification-Model
This project aims to build an image classification model using machine learning techniques to differentiate between images of family and friends. 
The model is implemented in Python using OpenCV for data cleaning and feature extraction, and Support Vector Machine (SVM) training for classification.
The model achieved high accuracy through feature extraction and Haar cascades for face detection.

## Prerequisites
To run this project, you will need:
Python 3.6 or later
OpenCV 4.0 or later
scikit-learn 0.22 or later

## Installation
Clone the repository:
git clone https://github.com/<your-username>/image-classification.git
Install the required packages:
pip install -r requirements.txt

## Usage
Add your dataset to the data folder. The dataset should contain two subfolders: family and friends, each containing the respective images.
Run the train.py script to train the model:
Run the predict.py script to predict the labels of new images
python predict.py --image <path-to-image>

## Credits
This project was developed by Manisha Kumari.

