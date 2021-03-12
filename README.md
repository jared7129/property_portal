# Real-EState-Website
Real Estate website for buying and selling houses made using django and bootstrap4. Any user can register and make a listing for selling a property

developed using python


# Steps to Install

i.e You must have python 3 and the django 3 environment installed in order to run the app. It also uses sqlite3 however it can also use postgres. The code is in the settings file

## Step 1 - Clone the project down locally

git clone https://github.com/jared7129/property_portal.git

## Step 2 - Run migrations

Run the following command - python manage.py migrate

## Step 3 - Create super user

Run the following command to create a super user to login - python3 manage.py createsuperuser

You can access the backend with the following link when the project is running:

http://127.0.0.1:8000/admin

### From here you can add realtors, listings and add contacts. When the user makes an enquiry from the listing, the will be saved in the database and will appear under contacts in the backend of the system


