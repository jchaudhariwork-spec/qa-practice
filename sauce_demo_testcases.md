# Sauce Demo Test Cases

## Test Case 1: Successful login
- Preconditions: User has a valid account (standard_user / secret_sauce)
- Steps:
  1. Navigate to https://www.saucedemo.com
  2. Enter valid username
  3. Enter valid password
  4. Click "Login"
- Expected Result: User is redirected to Products page.

## Test Case 2: Login with invalid password
- Preconditions: None
- Steps:
  1. Navigate to https://www.saucedemo.com
  2. Enter valid username
  3. Enter invalid password
  4. Click "Login"
- Expected Result: Error message "Epic sadface: Username and password do not match"
