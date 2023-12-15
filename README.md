# Simple Web Application

This is a simple web application using [Python Flask](https://flask.palletsprojects.com/en/3.0.x/) and [MySQL](https://www.mysql.com/) database. It is designed to demonstrate the development of Ansible Playbooks.

Below are the steps required to get this working on a base Linux system.

  * Install all required dependencies
  * Install and Configure the Web Server
  * Start Web Server

### 1. Install all required dependencies

Install Python and its dependencies using the following command:
```
apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb
```

### 2. Install and Configure Web Server

Install Python Flask and Flask MySQL dependencies:
```
pip install flask
pip install flask-mysql
```
  * Copy app.py or download it from a source repository
  * Configure database credentials and parameters

### 3. Configure Database

Start web server
```
FLASK_APP=app.py flask run --host=0.0.0.0
```

### 4. Start Web Server

Open a browser and go to the URL
```
http://<IP>:5000                            => Welcome
http://<IP>:5000/how%20are%20you            => I am good, how about you?
```
Replace <IP> with the actual IP address of your server.

Now you have the simple web application up and running. 
