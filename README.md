Image-Classification-Web-App-in-Flask-using-Machine-Learning
Image Classification App
This repository contains a web application for image classification. Users can upload an image, and the application predicts the image class using a pre-trained machine learning model. The app is built with Flask, providing an intuitive and user-friendly interface for easy image upload and classification.

Features
Image Upload: Allows users to upload images for classification.
Class Prediction: Displays the predicted class of the uploaded image.
About Page: Provides information about the project.
Error Handling: Displays error messages for invalid uploads or prediction failures.
Project Structure
flask_app.py: The main Flask application script that handles routing and prediction logic.
requirements.txt: List of required Python packages.
static/: Directory for static files (CSS, JavaScript, images).
css/: CSS files for styling the web pages.
images/: Directory to store uploaded images.
js/: JavaScript files for additional functionality.
models/: Directory containing the pre-trained machine learning models.
upload/: Directory for temporarily storing uploaded images.
templates/: Directory for HTML templates.
about.html: Template for the about page.
error.html: Template for displaying error messages.
index.html: Template for the home page.
upload.html: Template for the image upload page.
Installation
Prerequisites
Python 3.6 or higher
Virtual environment (recommended)
Steps
Clone the repository:

sh git clone https://github.com/yourusername/image-classification-app.git cd image-classification-app

Create and activate a virtual environment:

sh python3 -m venv venv source venv/bin/activate # On Windows, use venv\Scripts\activate

Install the required packages:

sh pip install -r requirements.txt

Usage
Run the Flask application:

sh python flask_app.py

Open your web browser and navigate to http://127.0.0.1:5000.

Upload an image and view the predicted class.

Model Information
The machine learning model used for image classification is a pre-trained model stored in the static/models/ directory. The model uses scikit-learn for classification and scikit-image for image processing.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. For major changes, please open an issue to discuss what you would like to change.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Flask - Web framework for Python
scikit-learn - Machine learning library
scikit-image - Image processing library
Bootstrap - Front-end framework for web development
