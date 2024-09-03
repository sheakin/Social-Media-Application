Social-Media-Application

A simple social media application built with Python and Django. This application allows users to perform basic social media actions such as adding posts, logging in, following other users, searching for posts, liking posts, and commenting on posts.

Features
User Authentication: Secure login and registration for users.
Post Management: Add, view, and manage posts.
User Interaction: Follow and unfollow other users.
Search Functionality: Search for posts and users.
Likes and Comments: Like and comment on posts from other users.
Installation
Follow these steps to get a copy of the project up and running on your local machine.

Prerequisites
Python 3.8 or higher
Django 4.x
PostgreSQL (or other supported databases)
Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/Social-Media-Application.git
cd Social-Media-Application
Create a Virtual Environment
bash
Copy code
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install Dependencies
bash
Copy code
pip install -r requirements.txt
Configure the Database
Update the DATABASES settings in social_media/settings.py to match your database configuration.

Apply Migrations
bash
Copy code
python manage.py makemigrations
python manage.py migrate
Create a Superuser
bash
Copy code
python manage.py createsuperuser
Run the Development Server
bash
Copy code
python manage.py runserver
Navigate to http://127.0.0.1:8000/ in your web browser to access the application.

Usage
Login: Use the login page to access your account.
Add Post: Create and publish new posts from your dashboard.
Follow Users: Search for and follow other users.
Like and Comment: Interact with posts by liking and commenting on them.
Search: Use the search feature to find posts and users.
Contributing
Feel free to fork the repository and submit pull requests. Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Django for the powerful web framework
PostgreSQL for reliable database management
Contact
For any questions or inquiries, please contact at linkedin " https://www.linkedin.com/in/sheakin-m-5159a9277/ "
