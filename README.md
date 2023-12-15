# Simple Web Application

This is a simple web application using Python Flask and MySQL database. It is designed for demonstrating the development of Ansible Playbooks.

## Getting Started

Follow these steps to set up and run the web application on a base Linux system.

### 1. Install all required dependencies

Install Python and its dependencies using the following command:

bash
sudo apt-get install -y python python-setuptools python-dev build-essential python-pip python-mysqldb

### 2. Install and Configure Web Server
Install Python Flask and Flask MySQL dependencies:

bash
Copy code
pip install flask
pip install flask-mysql
Copy app.py from this repository or download it:

bash
Copy code
git clone https://github.com/your/repo.git

### 3. Configure Database
Edit app.py to configure database credentials and parameters.

### 4. Start Web Server
Start the Flask web server:

bash
Copy code
FLASK_APP=app.py flask run --host=0.0.0.0

### 5. Test
Open a browser and navigate to the following URLs:

http://<IP>:5000 => Welcome
http://<IP>:5000/how%20are%20you => I am good, how about you?
Replace <IP> with the actual IP address of your server.

Now you have the simple web application up and running. This can be used as a basis for Ansible Playbook demonstrations.

Copy and paste this markdown content into your README.md file in your GitHub repository. Markdown is a lightweight and easy-to-read markup language supported by GitHub for formatting text. This format will render correctly on your GitHub repository page.
