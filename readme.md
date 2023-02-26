# Homework 2 developed by DBH
Clean looking profile with login features
# Installation
Install dependencies
```
pip install -r requirements.txt
```
Run server
```
python app.py
```
# Create `config.py` with these arguments:
```
USER_DB_DIR = 'database/logindb.txt'
IMAGES_ROOT = 'upload/'
SECRET_KEY = '<secret key>'
DATABASE_URI = '<your URI>'
UPLOAD_FOLDER = 'images'
ALLOWED_EXTENSIONS = {'png', 'jpg', 'jpeg', 'gif'}
```
# Tutorial
- `/login` - Login with your name and your password
- `/logout` - Logout from your account
- `/register` - Register an account
- `/upload/<filename>` - Access the uploaded file
- `/edit-pwd` - Change password
- `/edit-profile-pic` - Change profile picture

# Actions
-  Client can access image with route `/upload/<image_name>`
# Web page review
- Login page:

![Login page](login_img.jpg)

- Anonymous main page view:

![Register page](register_img.jpg)

- Logined main page view:

![Logined main page](main_page_img.jpg)

- Logined main page about:

![Logined main page 2](main_page_2_img.jpg)

- Change user password: 

![Change password](change_pwd_img.jpg)

- Change user avatar:

![Change avatar](change_avatar_img.jpg)
# phamvietanh-hw2
# hw2-wad
