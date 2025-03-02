# Automation Testing Assignment

## Overview

This project automates the testing of core functionalities of the noKodr platform using Selenium WebDriver. The scripts cover the following test scenarios:

- Basic Script: Browser navigation
- Signup Page Validation
- Login Page Validation
- Forgot Password Validation

## Technologies Used

- **Language:** Python
- **Framework:** Selenium WebDriver
- **IDE:** Jupyter Notebook

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository_link>
   cd <repository_directory>
   ```
2. Install dependencies:
   ```bash
   pip install selenium
   ```
3. Download and set up the WebDriver (ChromeDriver recommended).
4. Update the script with the correct WebDriver path if needed.

## Test Cases Implemented

### 1. Basic Script

- Opens Chrome browser.
- Navigates to the noKodr platform.

### 2. Signup Page Validation

- Checks for mandatory input fields (name, email, password, confirm password).
- Validates field-specific formats.
- Tests valid and invalid inputs.
- Ensures confirm password matches the password.
- Displays success or error messages accordingly.

### 3. Login Page Validation

- Checks for required fields (username, password).
- Ensures password meets format requirements.
- Tests valid and invalid login credentials.
- Displays appropriate success or error messages.

### 4. Forgot Password Validation

- Checks for mandatory email field.
- Validates email format.
- Tests valid and invalid email inputs.
- Displays success or error messages accordingly.

## Execution

Run each script in Jupyter Notebook or execute using:

```bash
jupyter notebook
```

Open the respective `.ipynb` file and run the cells sequentially.

## Contribution

Feel free to raise issues or create pull requests to enhance the project.

## Submission

Per assignment instructions, ensure the repository is public and share the link with HR.

