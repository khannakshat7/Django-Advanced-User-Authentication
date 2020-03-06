# Django Login and Registration


## Functionality

- Log in
    - via username & password
    - via email & password
    - via email or username & password
    - with a remember me checkbox (optional)
- Create an account
- Log out
- Profile activation via admin
- Reset password
- Remind a username
- Resend an activation code
- Change password
- Change email
- Change profile
- Admin Dashboard


## Installing

### Clone the project

```
git clone https://github.com/khannakshat7/Django-Advanced-User-Authentication.git
cd Django-Advanced-User-Authentication
```

### Install dependencies & activate virtualenv

```
python -m venv myproject
myproject\Scripts\activate

pip install django
pip install bootstrap4

```

### Apply migrations

```
python manage.py migrate
```

### Running

#### A development server

Just run this command:

```
python manage.py runserver
```
#### For User Signup
- Go to signup link and create a account
- Email goes to Admin with activation link (Currently email not working check emails folder)
- Admin has to activate the account using activation link



#### For Admin Login

Go to URL:
http://127.0.0.1:8000/admin

And Login Using:
username - admin
Password - admin

- Admin can view, Change, Delete, Change Permissions of user, Accept Request of user.
- Admin can accept the invitation of user by checking the active checkbox in user in admin panel


#### For User Login

- Go to login page to login
- If Admin activates your account then you can login using email and password
- Users can modify their profiles and change the email
