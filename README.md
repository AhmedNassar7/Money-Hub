# Money Hub

This is **Bank Management System** using **C++ ** designed to manage user and admin accounts in a bank system. The **Money Hub** application allows for secure management of financial accounts, including functionalities for users to view their accounts, make transactions, and for admins to manage both user and admin accounts.

## Table of Contents
- [Features](#features)
- [Login Options](#login-options)
- [Admin Functionalities](#admin-functionalities)
- [Main Admin Privileges](#main-admin-privileges)
- [User Functionalities](#user-functionalities)
- [Usage](#usage)
- [Default Admin Credentials](#default-admin-credentials)

---

## Features

### Overview
The Bank Management System provides separate functionalities for **admins** and **users**:
- **Admin**: Account creation, deletion, and management of users and other admins.
- **User**: Access to personal account information and financial transactions, including withdrawals and deposits.

### Login Options
1. **Admin Login**: Grants access to administrative tools and user management.
2. **User Login**: Allows users to manage their individual bank accounts.

---

## Admin Functionalities

Admins can perform the following actions:

1. **Display Admin Data**: View admin's personal and account details.
2. **Create Account for New User**: Add a new user account to the system.
3. **Delete User Account**: Remove an existing user account.
4. **Search for User Account**: Find and view user account details by username.
5. **Update User Account**: Modify user information, including name, age, and phone number.

---

## Main Admin Privileges

The **Main Admin** account (default credentials: `Username: Admin`, `Password: Admin`) has additional privileges:

1. **Create Account for New Admin**: Add a new admin account.
2. **Delete Admin Account**: Remove an existing admin account.
3. **Update Admin Account**: Modify admin details, such as name and contact information.
4. **Search for Admin Account**: Find and view admin account details by username.

---

## User Functionalities

Users can access the following features:

1. **Display Account Data**: View personal details and current balance.
2. **Withdraw Money**: Deduct a specified amount from the account balance.
3. **Deposit Money**: Add a specified amount to the account balance.

---

## Usage

Upon starting the application, users and admins will have the option to log in with their credentials to access their respective features.

- **Admin Mode**: Use an admin username and password to log in with administrative privileges.
- **User Mode**: Log in with a user account to access personal banking functionalities.

---

## Default Admin Credentials

The main admin account has the following default credentials:

- **Username**: `Admin`
- **Password**: `Admin`

Login -> Admin OR User

Admin { User Name - Password - Name - Age - Phone Number

    1 - Display His Data
    2 - Craete Account For New User
    3 - Delete User Account
    4 - Search For User Account
    5 - Update User Account

    The Main Admin { User Name: Admin - Password: Admin - Name - Age - Phone Number
        
        1 - Craete Account For New Admin
        2 - Delete Admin Account
        3 - Update Admin Account
        4 - Search For Admin Account
    
    }

}

User { User Name - Password - Name - Age - Phone Number - Amount Of Money

    1 - Display His Account Data
    2 - Withdraw Money
    3 - Deposit Money

}
