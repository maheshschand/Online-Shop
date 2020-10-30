# Online Shop
Online shop created using Django framework.

## Features
- Product catalog.
- Built a shopping cart using Django sessions.
- Manage customer orders.

## Demo
[Online Shop](https://online-shop-suven.herokuapp.com/)

## Run project locally
1. Clone the project  
    ```bash
    git clone https://github.com/maheshschand/Online-Shop.git  
    ```
2. Create a virtual evironment
    ```bash
    python -m venv venv
    ```
3. Activate your virtual environment  
    **For Windows**
    ```powershell
    cd venv\Scripts
    activate
    ```

    **For linux**
    ```bash
    source venv/bin/activate
    ```
    The shell prompt will include the name of the active virtual environment enclosed in parentheses, as follows:
    ```bash
    (venv) $
    ```
4. Locate the Online-Shop folder and run the following command
    ```bash
    (venv) $ pip install -r requirements.txt
    ```
5. Create the database migration for model.  
    Run the following command to create the database migration.
    ```bash
    (venv) $ python manage.py makemigrations
    ```
6. Migrate the database  
    Run the following command to migrate the database.
    ```bash
    (venv) $ python manage.py migrate
    ```
7. Create a administrator account  
    Run the following command to create a super user
    ```bash
    (venv) $ python manage.py createsuperuser
    ``` 
8. Run the following command to turn on the development server
    ```bash
    (venv) $ python manage.py runserver
    ```
    Enter in the browser: http://127.0.0.1:8000