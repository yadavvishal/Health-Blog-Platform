Health Blog Platform

Welcome to the Health Blog Platform! This is a Django-based web application where users can read and contribute articles on various health topics.

Setup
Prerequisites
Before you begin, ensure you have the following installed on your system:

Python (version 3.6 or higher)
Django (version 3.0 or higher)
Virtualenv (optional but recommended)

Installation
1- Clone this repository to your local machine:

git CLone https://github.com/yadavvishal/Health-Blog-Platform.git

2- Navigate into the project directory:

cd Health-Blog-Platform

3- Create a virtual environment (optional but recommended):
virtualenv venv

4- Activate the virtual environment:
On Windows:
venv\Scripts\activate

On macOS and Linux:
source venv/bin/activate

5- Install the required dependencies:
pip install -r requirements.txt

6- Perform database migrations:
python manage.py migrate

7- (Optional) Load initial data (e.g., categories, tags):
python manage.py loaddata initial_data

Usage

To run the development server, execute the following command:
python manage.py runserver

Once the server is running, you can access the health blog platform at http://localhost:8000 in your web browser.
