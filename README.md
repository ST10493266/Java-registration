# Java-registration
Part1 ass
# QuickChat Registration & Login System

##  Project Overview

This project is a simple Java-based **User Registration and Login System** designed to demonstrate fundamental programming concepts such as input validation, object-oriented programming, and unit testing. The system allows users to register with specific requirements and then log in using their credentials.

---

##  Purpose of the Project

The main goal of this project is to:

* Validate user input (username, password, phone number)
* Store user credentials temporarily
* Authenticate users during login
* Practice writing clean, modular Java code
* Demonstrate the use of unit testing with JUnit

---

##  Project Structure

The project consists of three main classes:

### 1. `Login.java`

This is the core class that handles:

* Username validation
* Password complexity checks
* Phone number validation
* User registration
* Login authentication
* Returning login status messages

### 2. `Registration.java`

This class contains the `main` method and is responsible for:

* Interacting with the user via console input
* Handling the registration process
* Managing the login process
* Controlling program flow using loops

### 3. `LoginTest.java`

This class is used for testing and includes:

* Unit tests for validation methods
* Tests for registration functionality
* Tests for login functionality
* Integration tests for full system flow

---

##  Features

*  Username validation (must contain underscore and be ≤ 5 characters)
*  Password complexity enforcement (minimum 8 characters, uppercase, number, special character)
*  Phone number validation (must follow +27 format)
*  Secure login verification
*  User-friendly feedback messages
*  Automated unit testing with JUnit

---

##  How the Program Works

1. The user enters their first and last name.
2. The system prompts the user to register by entering:

   * Username
   * Password
   * Phone number
3. The system validates each input:

   * If invalid, an error message is displayed and the user retries.
4. Once registration is successful, the user proceeds to login.
5. The user enters their username and password.
6. The system verifies credentials and:

   * Grants access with a welcome message if correct
   * Displays an error message if incorrect

---

##  Known Issues

* The success message in `Login.java` does not match the one checked in `Registration.java`, which may cause a loop issue.
* The phone number validation regex may not fully match standard South African numbers.
* User data is stored only in memory and is not persistent.

---

##  Testing

The project uses **JUnit 5** for testing. The test class includes:

* Validation tests (username, password, phone number)
* Registration tests (valid and invalid cases)
* Login tests (correct and incorrect credentials)
* Integration tests to simulate real usage

To run tests, ensure JUnit is properly configured in your IDE.

---

##  Future Improvements

* Store user data in a database or file
* Improve phone number validation
* Add graphical user interface (GUI)
* Implement password hashing for better security

---

##  Author

Registration Project(st10493266)

---


