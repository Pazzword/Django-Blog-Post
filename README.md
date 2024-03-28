# Django Blog Application

This is a simple blog application built using Django framework. It allows users to create, edit, and view blog posts.

## Features

- **Post List:** Displays a list of all blog posts.
- **Post Detail:** Allows users to view the details of a specific blog post.
- **Create Post:** Provides a form for users to create new blog posts.
- **Edit Post:** Allows users to edit existing blog posts.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Navigate to the project directory:

   ```bash
   cd django-blog
   
3. Install dependencies:

   ```bash
   pip install -r requirements.txt

4. Run migrations:

   ```bash
   python manage.py migrate

5. Create a superuser (admin):

   ```bash
   python manage.py createsuperuser

6. Start the development server:

   ```bash
   python manage.py runserver
   
7. Open your web browser and navigate to **http://127.0.0.1:8000/** to access the blog application.



Usage
Creating a Post: Click on the "New Post" button on the homepage to create a new blog post. Fill in the title and content of the post, then click "Save" to publish it.
Editing a Post: Click on the "Edit" button next to a post to modify its title or content.
Viewing a Post: Click on the title of a post to view its full content.


License
This project is unlicensed.
