# Virtual-Cloud-computing

Flask Docker Application
Overview
This repository contains a sample web application built using Flask and deployed in a Docker container.

Application Functionality
The application is a simple Flask web server that displays "------ " when accessed at the root URL.

Steps to Deploy
Set Up a Project Directory Create a new directory for your project and navigate into it.

Create a Flask Application Add app.py to define a simple Flask app.

Create a Requirements File Add requirements.txt to list the required Python packages. Flask Module has been used in this case.

Create a Dockerfile Write a Dockerfile to build an image for the Flask application.

Build the Docker Image Run docker build -t app . to build the image.

Run the Docker Container Start the container with docker run -p 5000:5000 app.

Author
-Name:Sudhanshu Kumar Verma

-Roll Number:G23ai2112
