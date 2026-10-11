# Java Selenium Authentication Test

## Overview
This project demonstrates web authentication testing using Java and Selenium WebDriver. It automates login and forgot-password workflows on the [Rahul Shetty Academy practice website](https://rahulshettyacademy.com/locatorspractice/).

## Features
- Launches the Microsoft Edge browser using Selenium WebDriver.
- Tests login with invalid credentials and retrieves the error message.
- Navigates to the forgot-password form.
- Enters user details and submits the reset form.
- Returns to the login page and attempts another login.
- Retrieves and displays messages from the web page.

## Technologies Used
- **Language:** Java
- **Automation Tool:** Selenium WebDriver
- **Build Tool:** Apache Maven
- **Browser:** Microsoft Edge

## Prerequisites
Before running this project, ensure you have installed:

- Java Development Kit (JDK)
- Apache Maven
- Microsoft Edge browser
- Git (optional, for version control)

## Project Structure

```text
Authentication-Test/
├── src/
│   └── main/
│       └── java/
│           └── Test.java
├── pom.xml
├── README.md
└── .gitignore
```

*The structure above is illustrative. Adjust it to match the actual location of `Test.java` in your project.*

## Setup and Execution

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Authentication-Test
```

### 2. Resolve Maven dependencies

```bash
mvn clean compile
```

### 3. Run the Java program

Run the `Test.java` file from your IDE, or use the appropriate Maven execution configuration if one is provided.

The program opens Microsoft Edge and executes the defined browser interactions.

## Notes
- The test uses a publicly accessible practice website. Its behavior and availability may change.
- The login credentials in the script are test inputs, not real account credentials.
- Selenium Manager may automatically manage the browser driver with compatible Selenium versions.
- The current script prints messages rather than asserting expected results. It is a basic automation example, not a comprehensive automated test suite.

## License and Attribution
This project is based on the Authentication Test example from the original repository:

[Java Selenium Automation Projects](https://github.com/amit-rakib/Java-Selenium-Automation-Projects)

Original author: amit-rakib.

Retain the original MIT license and attribution when redistributing the project, and describe any modifications made for this assignment.