# blog-repo
Django Blog Project:
This is a demo project for practicing Django. The idea was to build some basic blogging platform.

It was made using Python 3.6 + Django and database is SQLite. Bootstrap was used for styling. Testing is done using untitest module.


User has his own blog page, where he can add new blog posts.
Authenticated user can comment on posts made by other users. Home page is paginated list of all posts. Non-authenticated users can see all blog posts, but cannot add new posts or comment.
Clone This Project (Make Sure You Have Git Installed)

https://github.com/deepika-reddyb/blog-repo.git
Install Dependencies

pip install -r requirements.txt
Set Database (Make Sure you are in directory same as manage.py)

python manage.py makemigrations
python manage.py migrate
Create SuperUser

python manage.py createsuperuser
After all these steps , you can start testing and developing this project.
