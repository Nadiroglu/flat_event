1. -> npm install: This command installs the dependencies required for the React frontend. It reads the dependencies from the package.json file and installs them in the node_modules folder.
2. pipenv install: This command installs the dependencies required for the Flask backend using Pipenv. Pipenv is a tool that manages Python dependencies and virtual environments.
3. pipenv shell: This command activates the virtual environment created by Pipenv. It ensures that subsequent Python commands are executed within this environment, preventing conflicts with other projects.
4. Add your secret key at .env file in backend folder: This step involves adding a secret key to the .env file located in the backend folder. This secret key is typically used for encrypting session data, CSRF tokens, etc., to enhance security.
5. python seed.py: This command likely runs a Python script named seed.py. This script might be responsible for seeding the database with initial data or performing any other setup tasks.
6. python app.py: This command likely starts the Flask application. The app.py file is typically the entry point for the Flask application, where you define routes, configure the application, etc.

   FINALLY !!!!
   To summarize, the steps involve setting up dependencies for both the frontend and backend, activating the Python virtual environment,
   configuring environment variables for the backend, seeding the database (if needed), and finally starting the Flask application.

<img width="1722" alt="Screenshot 2024-06-07 at 1 58 52 PM" src="https://github.com/Nadiroglu/event-website-project/assets/150474907/4e268850-995e-4dd6-9bca-89373a8aa6bc">

# FlatEvent and Event Ticketing Website

This is a web application for managing events and ticketing, built using React for the frontend and Flask for the backend.

## Overview

The application allows users to browse and purchase tickets for various events. It includes features such as user authentication, event creation, ticket purchasing, and more.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Flask: A lightweight web framework for Python.
- SQLite: A relational database management system used for data storage.

## Setup Instructions

1. Clone the repository:

