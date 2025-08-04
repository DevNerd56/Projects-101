# Projects-101
Projects hand-on for your  final year college 

# 🕵️‍♂️ Fake Twitter Profile Detection System Using Machine Learning (ANN)

This project is a web-based application built with Django that uses an Artificial Neural Network (ANN) model to detect fake Twitter profiles based on specific user input parameters. It provides a simple interface for prediction and can be extended to work with other platforms like Instagram.

## 🧠 Features

- Detection of fake Twitter profiles using a trained ANN model.
- Web interface to input user profile data and get predictions.
- Pre-trained model integrated (`model.h5` and `model.json`).
- Built using Django, HTML/CSS (Materialize), and Python.

## 📂 Project Structure

Fake-Profile-Detection-System-Using-ML-ANN-main/
│
├── fpd/ # Django app
│ ├── static/ # Static files (CSS/JS)
│ ├── templates/ # HTML templates
│ ├── migrations/ # DB migrations
│ ├── model.h5 # Trained model (weights)
│ ├── model.json # Trained model architecture
│ └── views.py # Core logic and prediction
│
├── project/ # Django project settings
│
├── db.sqlite3 # SQLite database
├── manage.py # Django management script
├── requirements.txt # Dependencies
├── urls.py # Root URL configuration

## 🚀 Installation

### Prerequisites

- Python 3.8+
- pip

### Setup Instructions:

Create a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Apply migrations

bash
Copy
Edit
python manage.py migrate
Run the server

bash
Copy
Edit
python manage.py runserver
Visit the application
Open your browser and go to http://127.0.0.1:8000/

🖼️ UI Screens
Twitter Detection Page: /twitter

Instagram (dummy): /instagram

Result Page: /detect

📌 Model Details
Trained using Keras with TensorFlow backend.

Input parameters could include: number of followers, following count, tweet frequency, etc.

Architecture: JSON model + H5 weights.

📸 Logo
Logos used are located in the Logo/ directory.

📜 License
This project is for academic and research purposes. 

🙏 Acknowledgements
Materialize CSS
Django
TensorFlow & Keras

Note: This system assumes manual input or form submission. Twitter API integration is not included but can be added.
