## Moroccan Food Classifier

This project is a web application that classifies images of Moroccan food using a pre-trained convolutional neural network model. The application is built using Flask for the backend and TensorFlow/Keras for the machine learning model.

# Project Structure

moroccan_food_classifier/
├── model/
│ └── moroccan_food_classifier.h5
├── static/
│ └── uploads/
│ └── styles.css
├── templates/
│ └── index.html
├── app.py
├── requirements.txt
└── README.md

# Requirements

Python 3.6 or higher
Flask
TensorFlow
Pillow
Kaggle API token for dataset download

# Setup

## Clone the repository:

git clone https://github.com/yourusername/moroccan_food_classifier.git
cd moroccan_food_classifier

## Install the required Python packages:

pip install -r requirements.txt

## Run the Flask application:

python app.py

## Access the web application

Open your web browser and navigate to http://127.0.0.1:5000/
