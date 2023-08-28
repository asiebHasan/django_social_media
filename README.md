# Django Social Media Project

This is a Django project that demonstrates various features of the Django framework and related technologies. The project focuses on building a social media platform with features such as user registration, authentication, social authentication, AJAX views, follow system, activity stream, image thumbnails, and more.

## Features

- Using the Django authentication framework
- Creating user registration views
- Extending the user model with a custom profile model
- Adding social authentication with Python Social Auth
- Creating many-to-many relationships
- Customizing behavior for forms
- Using jQuery with Django
- Building a jQuery bookmarklet
- Generating image thumbnails using easy-thumbnails
- Implementing AJAX views and integrating them with jQuery
- Creating custom decorators for views
- Building AJAX pagination
- Building a follow system
- Creating many-to-many relationships with an intermediary model
- Creating an activity stream application
- Adding generic relations to models
- Optimizing QuerySets for related objects
- Using signals for denormalizing counts
- Storing item views in Redis

## Installation

To get started with the Django Social Media Project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/django-social-media.git
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. **Navigate to the project directory:**

    ```bash
    cd django-social-media
    ```

4. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Run database migrations:**

    ```bash
    python manage.py migrate
    ```

6. **Start the development server:**

    ```bash
    python manage.py runserver
    ```

7. **Access the application:**

    Open your web browser and go to `http://localhost:8000/`.

8. **Explore the features:**

    Use the application to explore various features like user registration, authentication, social authentication, image uploading, follow system, and more.

Feel free to modify and extend the project according to your needs!