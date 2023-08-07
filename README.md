## Simple Web Application
This is a simple web application using Python Flask. This is used in the demonstration of development of Ansible Playbooks.

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

