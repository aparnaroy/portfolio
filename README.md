# Personal Portfolio

## MLH Production Engineering Fellowship (Meta)

This project showcases the range of technologies I mastered during the MLH fellowship, offering a firsthand view of my evolving expertise and the enhancement of my abliities.

## Visit My Portfolio: https://aparna.duckdns.org/

## Features

- Deploying a Flask website on a virtual private server (VPS) via a Digital Ocean droplet with CentosOS (Linux)
- Leveraging Jinja for dynamic HTML page rendering and both Bootstrap and custom CSS for mobile-responsive design
- Implementing Flask app routing for the various pages of the website
- Harnessing MySQL to post and get/retrieve timeline entries
- Establishing a CI/CD pipeline using Bash scripts, Docker containers, and GitHub Actions for automated testing and deployment on the VPS
- Securing the website with HTTPS certification using NGINX
- Containerizing the infrastructure using Docker and Docker Compose comprising 3 containers: myportfolio, mysql, and nginx
- Automating unit testing and integration testing on API endpoints and the MySQL database on pushes or pull requests to the main branch

## Installation

Make sure you have python3 and pip installed

Create and activate virtual environment using virtualenv

```bash
$ python -m venv python3-virtualenv
$ source python3-virtualenv/bin/activate
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all dependencies!

```bash
pip install -r requirements.txt
```

## Usage

Create a .env file using the example.env template (make a copy using the variables inside of the template)

Start flask development server

```bash
$ export FLASK_ENV=development
$ flask run
```

You should get a response like this in the terminal:

```
❯ flask run
 * Environment: development
 * Debug mode: on
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

You'll now be able to access the website at `localhost:5000` or `127.0.0.1:5000` in the browser!
