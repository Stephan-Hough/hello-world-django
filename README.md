# Hello World Django App

This is a simple Django application that displays "Hello, World!" on the homepage.

## Prerequisites

- Python 3.x
- Django

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/hello-world-django.git
   cd hello-world-django
   ```

2. Create a virtual environment:

   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

## Running the Application

1. Apply migrations:

   ```
   python manage.py migrate
   ```

2. Run the development server:

   ```
   python manage.py runserver
   ```

3. Open your web browser and go to `http://127.0.0.1:8000/` to see "Hello, World!" displayed on the page.

## License

This project is licensed under the MIT License - see the LICENSE file for details.