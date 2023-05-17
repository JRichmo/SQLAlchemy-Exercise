# SQLAlchemy-Exercise

Flask Application README
This repository contains a Flask application that utilizes Flask framework, Flask-DebugToolbar extension, and SQLAlchemy for database functionality.

1. Installation
Clone the repository to your local machine.

git clone <repository-url>

2. Navigate to the project directory.

cd <project-directory>

3. (Optional) Create and activate a virtual environment to isolate the project dependencies.

python3 -m venv env
source env/bin/activate
  
4. Install the required dependencies using pip.

pip install -r requirements.txt

Configuration
Open the config.py file and update the following configurations if needed:

SQLALCHEMY_DATABASE_URI: Set the URI for your PostgreSQL database. The current default value is "postgresql:///blogly". Modify it to match your own database configuration.
SQLALCHEMY_TRACK_MODIFICATIONS: Set it to False to disable tracking modifications. Change it if necessary.
SECRET_KEY: Set a secret key for session encryption. Modify it to your own secret key.

  
Usage
1. Run the Flask application.

flask run

2. Access the application in your web browser at http://localhost:5000.

Features
The application provides a basic Flask setup with routes, templates, and models.
It uses SQLAlchemy as the ORM for interacting with the database.
The Flask-DebugToolbar extension is included for debugging and development features.
Contributing

Feel free to customize this README file according to your project's specific details and requirements.
