Flask Web App with CI/CD 🚀

A simple Flask web application integrated with a CI/CD pipeline using GitHub Actions.
This project demonstrates how continuous integration and continuous deployment can be applied to even the simplest apps, ensuring reliability and automation.

📌 Features

Flask web app serving a homepage (Hello, CI/CD!)

Unit tests with pytest

GitHub Actions workflow for:

Installing dependencies

Running tests

Deploying the app automatically (Heroku/Render)

Fully automated pipeline triggered on every push to main

🛠 Tech Stack

Python 3.10

Flask

Pytest (for testing)

Gunicorn (for deployment)

GitHub Actions (CI/CD)

Heroku / Render (deployment platform)

⚙️ Project Structure
flask-ci-cd/
│── app.py                # Main Flask application
│── requirements.txt      # Project dependencies
│── Procfile              # For Heroku deployment
│── templates/
│    └── index.html       # HTML template
│── tests/
│    └── test_app.py      # Unit tests
│── .github/
│    └── workflows/
│         └── ci.yml      # GitHub Actions workflow
│── README.md             # Project documentation

🚀 Getting Started
1. Clone the repository
git clone https://github.com/your-username/flask-ci-cd.git
cd flask-ci-cd

2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

3. Install dependencies
pip install -r requirements.txt

4. Run the app locally
python app.py


Open in your browser: http://127.0.0.1:5000/

🧪 Running Tests
pytest


Expected output:

tests/test_app.py .                                          [100%]
1 passed in 0.XXs

🔄 CI/CD Workflow

Trigger: Push or PR to main branch

Workflow steps:

Checkout repo

Set up Python

Install dependencies

Run tests

Deploy to cloud (if tests pass ✅)

Workflow file: .github/workflows/ci.yml

🌍 Live Demo

🔗 http://127.0.0.1:5500/

📸 Screenshots 
Home Page – “Hello, CI/CD!”

GitHub Actions Workflow – All tests passing

Deployment Logs – Successful deploy

✨ Learning Outcomes

Basics of Flask web apps

Setting up unit tests with pytest

Building a CI/CD pipeline with GitHub Actions

Deploying a Python app on Heroku/Render
