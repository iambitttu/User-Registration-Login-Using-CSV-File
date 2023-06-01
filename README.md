# Registration and Login System

## Introduction
The Registration and Login System is a Python-based program that enables users to register, login, and manage their accounts securely. This system utilizes file handling and regular expressions to validate and store user information. The user's email and password are checked using regular expressions to ensure they meet the required format. The system provides functionalities such as registration, login, and password recovery.

## Tools Used
- Python: Programming language used for implementing the system.
- File Handling: Utilized for reading and writing user information to a CSV file.
- Regular Expressions: Employed to validate email and password formats.

## Functionality
1. User Registration:
   - Users can register by providing their email and password.
   - The email and password are validated using regular expressions to ensure proper formats.
   - If the registration is successful, the user's email and hashed password are stored in a CSV file.

2. User Login:
   - Users can log in by providing their registered email and password.
   - The login information is compared with the stored user credentials in the CSV file.
   - If the login is successful, the system displays a welcome message and saves the user's ID for further actions.

3. Password Recovery:
   - Users can recover their password in case they forget it.
   - The system prompts users to enter their registered email address.
   - If the email exists in the CSV file, a temporary password is generated and sent to the user's email.

4. CSV File Management:
   - User information, including email and hashed password, is stored in a CSV file.
   - The file is created if it doesn't exist, and new user data is appended to it.

## Usage
1. Registering a User:
   - The user provides their email and password.
   - The system validates the email and password formats using regular expressions.
   - If the registration is successful, the user's email and hashed password are stored in the CSV file.

2. Logging in:
   - The user provides their registered email and password.
   - The system compares the provided login information with the stored user credentials.
   - If the login is successful, the system displays a welcome message and saves the user's ID.

3. Password Recovery:
   - The user provides their registered email address.
   - The system checks if the email exists in the CSV file.
   - If the email is found, a temporary password is generated and sent to the user's email for password recovery.

4. CSV File Management:
   - The user data, including email and hashed password, is stored in a CSV file.
   - The CSV file is created if it doesn't exist, and new user data is appended to it.

## Conclusion
The Registration and Login System provides a secure and convenient way for users to register, login, and manage their accounts. By utilizing regular expressions and file handling, the system ensures proper validation and storage of user information. The functionalities of registration, login, and password recovery empower users to access and manage their accounts effectively. The CSV file serves as a reliable storage mechanism for user data. By following the outlined instructions and using the provided tools, users can successfully utilize the Registration and Login System for their application.
