# ACEest Gym DevOps Project

## Overview

This project is a Flask-based web application developed for ACEest Fitness & Gym. It demonstrates a complete DevOps workflow including version control, testing, containerization, and CI/CD automation.

## Features

* Flask web application
* Automated testing using Pytest
* CI/CD pipeline using GitHub Actions
* Docker containerization support

## Local Setup and Execution

1. Clone the repository:
   git clone https://github.com/2024tm93649-bit/aceest-gym-app.git

2. Navigate to project folder:
   cd aceest-gym-app

3. Install dependencies:
   pip install -r requirements.txt

4. Run the application:
   python app.py

5. Open browser:
   http://127.0.0.1:5000/

## Running Tests

Run the following command:
python -m pytest

## CI/CD Pipeline (GitHub Actions)

* The pipeline is triggered on every push and pull request.
* It automatically installs dependencies and runs tests.
* Ensures code quality before deployment.

## Jenkins Integration (Concept)

Jenkins acts as a build server in the CI/CD pipeline:

* Pulls code from GitHub repository
* Installs dependencies
* Runs tests
* Builds the application in a controlled environment

## Conclusion

This project demonstrates a complete DevOps lifecycle from development to automated testing and deployment readiness.
