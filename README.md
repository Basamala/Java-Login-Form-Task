# Java Login Form Task

## Description
A simple Java AWT login form that validates user input and authenticates hard-coded users.

## Features
- Checks for empty username and password fields.
- Checks whether the username exists.
- Validates the password and selected role.
- Displays a welcome page after successful login.
- Disables the Login button after three incorrect passwords.

## Test Users

| Username | Password | Role |
|---|---|---|
| student1 | 1234 | Student |
| ta1 | 5678 | TA |
| prof1 | abcd | Professor |

## Technologies
- Java
- AWT
- VS Code

## How to Run
Compile the program:

`javac -d out src/LoginFormTask.java`

Run the program:

`java -cp out LoginFormTask`

## Screenshots
See the `screenshots` folder for validation and login test results.
