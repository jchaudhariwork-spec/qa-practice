\# Sauce Demo Test Cases



\## Test Case 1: Successful login

\- Preconditions: User has a valid account (standard\_user / secret\_sauce)

\- Steps:

&nbsp;   1. Navigate to https://www.saucedemo.com

&nbsp;   2. Enter valid username

&nbsp;   3. Enter valid password

&nbsp;   4. Click "Login"

\- Expected Result: User is redirected to the Products page



\## Test Case 2: Login with invalid password

\- Preconditions: None

\- Steps:

&nbsp;   1. Navigate to https://www.saucedemo.com

&nbsp;   2. Enter valid username

&nbsp;   3. Enter invalid password

&nbsp;   4. Click "Login"

\- Expected Result: Error message "Epic sadface: Username and password do not match" is displayed



\## Test Case 3: Verify the product is listed

\- Preconditions: None

\- Steps:

&nbsp;   1. Navigate to https://www.saucedemo.com

&nbsp;   2. Enter a valid username

&nbsp;   3. Enter a valid password

&nbsp;   4. Click "Login"

&nbsp;   5. Observe that products are listed on the page

\- Expected Result: Products are displayed with names and images on the page



\## Test Case 4: Verify filtering option on Products page

\- Preconditions: None

\- Steps:

&nbsp;   1. Navigate to https://www.saucedemo.com

&nbsp;   2. Enter a valid username

&nbsp;   3. Enter a valid password

&nbsp;   4. Click "Login"

&nbsp;   5. Click the Sort dropdown on the top right of the Products page

&nbsp;   6. Select different filter options (e.g., Name Z→A, Price Low→High)

&nbsp;   7. Verify that the products are reordered correctly according to the selected filter

\- Expected Result: Each filtering option should reorder the products as intended



