# Bank-Managenent-System
Online Banking Management System

-----------------------------------------------------------------------------------------------------------------------------------------------------------

This is a simple web-based application developed in Python and Django Framework. 
The main goal of this project is to provide bank account holders with an online platform to make some transactions. 
The application allows the account holders of a certain bank to withdraw and deposit. 
It has a pleasant user interface using Tailwind CSS Framework and this application consists of user-friendly features and functionalities.

This Bank Management System Project is accessible to all registered bank account holders. 
The account holders can register their account by filling in all the required fields on the registration form page. 
This banking system application requires the newly registered users to deposit money as the starting balance of their online account. 
Here, users can deposit a new amount to their account and withdraw from their current balance. 
The system also lists all the transaction records of the users that were done using the application. 
On the Transaction Records page, users can filter the records to show between two dates.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

-: FEATURES :-

Login Page
Registration Page
Home/Transaction List Page
Deposit Starting Balance
Deposit to Account
Withdraw Amount from Account
Filter Transaction Records Between 2 dates
Logout Page

-----------------------------------------------------------------------------------------------------------------------------------------------------------
ScreenShot - MAIN PAGE of BANK MANAGEMENT SYSTEM

<img width="1440" alt="Main Page" src="https://user-images.githubusercontent.com/76025681/204486620-affd6f35-7100-46f2-9d55-cd42fb3906b0.png">

-----------------------------------------------------------------------------------------------------------------------------------------------------------
How to Run

Download/Install the following
- Python (I used v3.9.1)
- PIP (for python modules installation)

Setup/Installation

- Download and Extract the provided source code zip file. (download button is located below)
- Open your Terminal/Command Prompt window. (make sure to add "python" and "pip" in your environment variables)
- Change the working directory to the extracted source code folder. i.e. 
    cd C:\Users\Personal-23\Desktop\django_banking
- Run the following commands:
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver
- Keep the terminals open and running.
- Open a web browser and browse the Simple Banking Management System 
    http://localhost:8000/ or http://127.0.0.1:8000/
    http://127.0.0.1:8000/admin for the Django's Admin Site.

- Default Admin Access (Login only @ Django Admin Panel)
    Email: admin@mail
    Password: admin123

- Sample User Access
    Email: mcooper@mail
    Password: test#123
    
-----------------------------------------------------------------------------------------------------------------------------------------------------------
