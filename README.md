# Dockerizing-a-Python-Flask-Application
Creating a automation Container which handles a Python Application 

Overview

Creating a Docker Container for a python Application.
Run the container from Docker, 
1) Install Docker first
      See: how-to-install-docker

2) Create A app.py file for Python code

3) Create a docker image
      Run docker build -t my-flask-app .

 4) Run the Docker container based on the image
      Run docker run -p 8080:5000 flask-docker-app

 5) Verify the result
      curl localhost:8080
       Or open http://localhost:8080 in your browser 

  
