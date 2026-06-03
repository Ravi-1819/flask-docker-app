 *Dockerized Flask App on AWS EC2*

** Project Overview

This project demonstrates how to containerize and deploy a Flask web application using Docker on an AWS EC2 instance.

**Technologies Used

* Python
* Flask
* Docker
* Docker Compose
* Gunicorn
* AWS EC2
* Git & GitHub
* Docker Hub

## Project Structure

```text
flask-docker-app/
│
├── app.py
├── dockerfile
├── docker-compose.yml
├── requirements.txt
└── templates/
    └── index.html
```

## Features

* Flask web application
* Docker containerization
* Gunicorn production server
* AWS EC2 deployment
* Docker Hub image publishing
* GitHub version control

## Docker Build

```bash
docker build -t flask-app .
```

## Run Container

```bash
docker run -d -p 5000:5000 --name flask-container flask-app
```

## Docker Hub Image

```bash
docker pull ravi1819/flask-app:v1
```

## Deployment

The application was deployed on an AWS EC2 instance using Docker and accessed through port 5000.
done my Flask App project 
