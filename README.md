# Money Hub

This repository contains a C++ project for a **Bank Management System** that manages accounts for users and admins. The system provides functionality for both users and admins, enabling account management, financial transactions, and administrative tasks.

## Features

### Login Options
- **Admin Login**: Provides admin-level privileges.
- **User Login**: Allows users to manage their bank accounts.

### Admin Functionalities
Admins have access to the following features:
1. **Display Admin Data**: View personal details and account information.
2. **Create Account for New User**: Add a new user account to the system.
3. **Delete User Account**: Remove an existing user account.
4. **Search for User Account**: Find and view a user account by username.
5. **Update User Account**: Modify user details such as name, age, and phone number.

#### Main Admin Privileges
The main admin (default credentials: **Username**: Admin, **Password**: Admin) has additional capabilities:
1. **Create Account for New Admin**: Add a new admin to the system.
2. **Delete Admin Account**: Remove an existing admin account.
3. **Update Admin Account**: Modify admin details.
4. **Search for Admin Account**: Find and view an admin account by username.

### User Functionalities
Users have access to the following features:
1. **Display Account Data**: View personal details, including balance.
2. **Withdraw Money**: Deduct a specified amount from their account.
3. **Deposit Money**: Add a specified amount to their account balance.


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
