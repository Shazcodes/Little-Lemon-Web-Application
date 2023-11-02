# Little Lemon Web Application

Welcome to the Little Lemon Web Application! This is a comprehensive web solution designed for restaurant operations management. Below you will find detailed information about the project, including its features, technologies used, and instructions on how to set it up and get it running.

## Description

Little Lemon is a web application crafted to streamline and enhance the efficiency of restaurant management tasks. It is developed using the Django framework, which is known for its high-level Python web framework that encourages rapid development and clean, pragmatic design.

## Features

- **Menu Management**: A robust system to manage the restaurant's menu, including dishes, prices, and descriptions.
- **Image Gallery**: A feature to display the restaurant's ambiance and popular dishes.
- **Contact Information**: A section to provide customers with essential contact details and location information.

## Technologies Used

- **Programming Language**: Python
- **Web Framework**: Django
- **Database**: SQLite
- **Frontend**: HTML, CSS
- **APIs**: Django REST Framework for RESTful API services
- **Authentication**: Token-based authentication with Djoser

## Installation and Setup

1. **Clone the repository**: Get a copy of the source code on your local machine.
2. **Set up a virtual environment**: It's recommended to create a virtual environment for the project dependencies.
3. **Install dependencies**: Install the required packages using `pip install -r requirements.txt`.
4. **Database setup**: Apply the migrations to set up the database schema with `python manage.py migrate`.
5. **Create an admin user**: Set up a superuser for the admin panel with `python manage.py createsuperuser`.
6. **Run the server**: Start the development server using `python manage.py runserver`.
7. **Access the application**: Open a web browser and navigate to `http://127.0.0.1:8000/`.

## Usage

- **Admin Panel**: Access `http://127.0.0.1:8000/admin` to manage the restaurant's offerings.
- **API Endpoints**: Utilize the RESTful endpoints for programmatic access to the application's data.

## Contributing

Contributions to the Little Lemon Web Application are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-sourced under the MIT License.
