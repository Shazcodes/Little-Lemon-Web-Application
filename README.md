# Little-Lemon-Web-Application
Description
Little Lemon is a web application designed to manage restaurant operations efficiently. This project is built using Django, a high-level Python web framework that encourages rapid development and clean, pragmatic design.

Features
Menu Management: Easily manage your restaurant's menu, including dishes, prices, and descriptions.
Image Gallery: Showcase your restaurant's ambiance and popular dishes with an image gallery.
Contact Information: Provide your customers with essential contact information and location details.
Getting Started
Prerequisites
Python 3.9 or higher
Django 3.2 or higher
SQLite (or any other database of your choice)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Shazcodes/Little-Lemon-Web-Application.git
Navigate to the project directory:

bash
Copy code
cd Little-Lemon-Web-Application
Install the required packages:

Copy code
pip install -r requirements.txt
(Note: The requirements.txt file is assumed to be present in the project. If it's not, you'll need to install Django manually.)

Apply the migrations:

Copy code
python manage.py migrate
Create a superuser account:

Copy code
python manage.py createsuperuser
Run the development server:

Copy code
python manage.py runserver
Open your browser and navigate to http://127.0.0.1:8000/ to see the application in action.

Usage
Visit the admin panel at http://127.0.0.1:8000/admin to manage the restaurant's menu and other settings.
Explore the website to see the restaurant's menu, image gallery, and contact information.
Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues to discuss potential changes or improvements.

License
This project is licensed under the MIT License.
