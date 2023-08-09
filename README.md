## Simple Web Application
This is a simple web application using Python Flask. Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries.

#### Below are the steps required to get this working on a base linux system.
**a) Install all required dependencies
b) Install and Configure Web Server
c) Start Web Server**


## 1)  Install all required dependencies
   Python and its dependencies
   
      apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb

## 2)  Install and Configure Web Server
Install Python Flask dependency

      pip install flask
      
Copy app.py or download it from source repository

## 3) Start Web Server
Start web server

    FLASK_APP=app.py flask run --host=0.0.0.0

## 4) Test
Open a browser and go to URL

    http://<IP>:5000                            => Welcome
    http://<IP>:5000/how%20are%20you            => I am good, how about you?

