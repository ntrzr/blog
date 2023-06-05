## Blog Page Readme

## How to run
1. Create a virtualenv named venv using `python -m venv venv`
2. Connect to virtualenv using `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Linux)
3. From the project folder, install packages using `pip install -r requirements.txt`
4. Now environment is ready. Run it by `python .\blog_project\main.py`
5. Also pip install these: `flask` `flask_bcrypt` `flask_login` `flask_sqlalchemy`


## User Registration
The blog page provides a user registration feature, allowing new users to sign up for an account. To register, follow these steps:

1. Navigate to the registration page by clicking on the "Register" link.
2. Fill out the registration form, providing a unique username, email address, and password.
3. Click the "Register" button to create your account.
4. Upon successful registration, you will be redirected to the login page.


## User Login
Existing users can log in to their accounts using the following steps:

Access the login page by clicking on the "Login" link.
Enter your username and password in the respective fields.
Click the "Login" button to authenticate your credentials.
If the provided information is correct, you will be redirected to the main page.


## Database Management
The blog page utilizes an SQLite database to store user information and blog posts. The necessary database tables and fields are automatically created during the migration process described in the "Getting Started" section.


## Post Creation
Logged-in users have the ability to create new blog posts. To create a post, follow these steps:

1. After logging in, navigate to the blog creation page.
2. Fill out the required fields, such as title and content, in the blog post form.
3. Optionally, add any relevant tags or categories.
4. Click the "Create" button to publish your blog post.
5. Upon successful creation, you will be redirected to the main page, where your new post will be displayed.


## Post Deletion
Users can delete their own blog posts. To delete a post, follow these steps:

1. Locate the post you wish to delete on the main page or your user profile.
2. Click on the delete icon or link associated with the post.
3. Confirm the deletion when prompted.
4. The post will be permanently removed from the database.


## Post Editing
Users can edit their own blog posts. To edit a post, follow these steps:

1. Find the post you want to edit on the main page or your user profile.
2. Click on the edit icon or link associated with the post.
3. Make the desired changes to the post title, content, or other fields.
4. Save the changes
