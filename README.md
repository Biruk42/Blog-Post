# Blog Post

## Introduction
This is a Flask-based blog application that allows users to create, read, update, and delete blog posts. Users can register for an account, log in, and interact with the blog by writing comments on posts. The application features user authentication, database integration, and dynamic rendering of blog posts using Flask and SQLAlchemy.

## Features
- **User Authentication**: Users can register for an account and log in securely using password hashing and Flask-Login.
- **Blog Post Creation**: Authenticated users can create new blog posts, including a title, subtitle, body text, and image URL.
- **Blog Post Display**: All blog posts are dynamically displayed on the homepage, with options to read more, view comments, and interact with other users.
- **Comments**: Users can write comments on blog posts, view comments made by other users, and delete their own comments if desired.
- **Admin Panel**: Certain admin-only functionalities are available, such as deleting comments and managing blog posts.

## Technologies Used
- Flask: A lightweight web framework for Python.
- SQLAlchemy: An Object-Relational Mapping (ORM) library for Python, used for database integration.
- Flask-Login: Provides user session management for Flask applications.
- Flask-CKEditor: Integrates the CKEditor rich text editor with Flask applications for creating blog post content.
- Flask-Gravatar: Provides Gravatar image URLs for user profile pictures.
- Bootstrap: A front-end framework for building responsive and mobile-first websites.

## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Set up a virtual environment and activate it.
4. Run the Flask application using `flask run`.

## Credits
This blog application was created by Biruk. Contributions are welcome and encouraged.

