# Grocery Store Website (Educational Project)

This repository contains the code for a grocery store website built for **educational purposes**. The project serves as a learning exercise in web development and DevOps practices and is **not intended for actual commercial use**.

## Project Features

- **Frontend:** HTML, CSS, JavaScript for dynamic and interactive user interfaces.
- **Backend:** Django as the primary framework for server-side functionality.
- **Database:** SQLite for managing and storing data. PostgreSQL will replace SQLite in future.
- **DevOps Focus:** Docker files and configurations will be created to containerize the project and streamline deployment processes.

## Purpose

This project is designed to:
1. Enhance web development skills by creating a feature-rich application.
2. Apply and learn DevOps practices, including containerization and deployment using Docker.

## How to Run the Project

1. **Clone the repository:**
   git clone https://github.com/dragoura/ecommerce.git

2. **Navigate to the project directory:**
   cd grocery-store-website

3. **Set up a virtual environment:**
   python -m venv venv
   source venv/bin/activate  

4. **Install dependencies:**
   pip install -r requirements.txt

5. **Apply migrations:**
   python manage.py migrate

6. **Run the development server:**
   python manage.py runserver

7. **Access the application in your browser at http://127.0.0.1:8000**

## License

This project is open-source and distributed under the **MIT License.**