# Inventory-Management
This is a web-based inventory management system developed with Django. It provides a robust platform for real-time tracking, management, and reporting of inventory items, helping to prevent stockouts and improve overall efficiency. The application is deployed and live on Render, leveraging a production-ready stack with Gunicorn and Nginx.

## Features

Real-time Low-Stock Alerting: Automatically sends alerts when an item's quantity falls below a predefined threshold, preventing stockouts.

Comprehensive Item Management: Provides full CRUD (Create, Read, Update, Delete) functionality for all inventory items.

Intuitive Dashboard: A clean and easy-to-use dashboard to get a quick overview of current stock levels.

Secure Authentication: Includes secure user login, logout, and registration functionalities.

## Technologies Used

Backend: Python, Django

Frontend: HTML, CSS

Database: SQLite3

Styling: Django Crispy Forms, Bootstrap 5

Deployment: Render

Production Server: Gunicorn

Reverse Proxy: Nginx


Project Setup Guide

## Prerequisites

- Python 3.x
- pip (Python package installer)

## Setting Up the Development Environment

### 1. Clone the Repository

```bash
git clone Inventory-Management
cd Inventory-Management
```

### 2. Create a Virtual Environment

Create a new virtual environment in a local folder named `.venv`:

```bash
python3 -m venv .venv
```

### 3. Activate the Virtual Environment

#### On Unix or MacOS:
```bash
source .venv/bin/activate
```

#### On Windows:
```bash
.venv\Scripts\activate
```

Once activated, your terminal prompt should change to indicate you're working in the virtual environment.

### 4. Install Dependencies

Install all required packages using pip:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the development server:

```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`

## Development

- The virtual environment must be activated whenever you're working on the project
- To deactivate the virtual environment when you're done, simply run:
  ```bash
  deactivate
  ```

## Project Structure

```
project/
├── .venv/              # Virtual environment directory
├── requirements.txt    # Project dependencies
├── manage.py          # Django management script
└── ...                # Other project files
```

## Additional Notes

- Make sure to never commit the `.venv` directory to version control
- Keep `requirements.txt` updated when adding new dependencies
- Run `pip freeze > requirements.txt` to update the dependencies list





