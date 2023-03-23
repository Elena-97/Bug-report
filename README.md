# Bug-report

Below are some Bug report samples that I wrote while working on previos projects.


**Title**:Order is successfully with invalid shipping address.
**Description**: The order is accepted with an invalid shipping address.

**Precondition**:
1. Navigate to https://demo.prestashop.com/.
2. Select a product in to the cart.
3. Click on the "Proceed to checkout" button.

**Steps to reproduce**: 
1. Insert valid data in the "Personal information" fields.
2.Check the "Customer data privacy" and "Terms and conditions and privacy policy and press "Continue" button.
3. Insert invalid data in the "Address" page fields and press "Continue" button.
4. Select shipping method by "PrestaShop" and Click the "Continue" button.
5. Select "Pay by bank wire" from Payment option.
6. Check the "terms of service" Check box.
7. Click on the "Place order" button.

**Expected results**: The successfully order must contain a valid shipping address.
**Actual results**: The order succeed with invalid shipping address.
**Occurrence**: systematic
**Severity**: Medium
**Piority**: High
**Module**: Order
**Browser**: Chrome

------------------

**Title**:Login failed
**Description**: When I try to login in my account the log in fail.
**Precondition**: Navigate to https://demo.prestashop.com/

**Steps to reproduce**: 
1. Click to "Sing in" item
2. Insert data of the account in the Email and Password fields.
3. Press "Sing in" button.

**Expected results**: The log is successfully and the home page is displayed.
**Actual results**: The login is failed, and a error message "Authentication failed." is displayed.
**Occurrence**: Systematic
**Severity**: High
**Priority**: High
**Browser**: Edge
**Module**: Sing in.

--------------------


**Title**:Logged out after refresh
**Description**: In the My account page when the "Refresh" button is pressed the site log out from the account..
**Preconditions**: Navigate to https://demo.prestashop.com/

**Steps to reproduce**.
1 Click on the "Sing in "item.
2. Login in the account.
3. Refresh the page.

**Expected results**: I am logged in the account after refresh and my account page is displyed.
**Actual results**: The home page is displayed after refresh and the page log-out my account.
**Additional info**: This issue is reproduce in all categories of the site.
**Occurrence**: Systematic
**Severity**:High
**Priority**: High
**Module**: Sing in.
**Browser**: Edge.

------------------

**Title**: New account with data of existent account.
**Description**: Can create a new account with data of existent one.
**Precondition**: 
Navigate https://demo.prestashop.com/
Click on the "Sing" in item.

**Steps to reproduce**:
1. Click on the No account? Create one here
2. Insert in the First Name field - Logofatu and Last Name field- Elena
3. Insert in Email field-elena_logofatu97@yahoo.com and in Password field-teste
4.Blank "Birthdate" field and check all check-boxes.
5.Press Save" button.

**Expected results**: The new account creation failed and a error notification "The account already exists.
**Actual results**: The New account can be created with data of existent account and a notification is missing.
**Occurrence**: Systematic
**Severity**: Medium
**Priority**: Medium
**Broeser**:Chrome, Edge.


-------------------

**Title**Account created with invalid data.
**Description**: The new account is successfully created with invalid email address.
*8Precondition**: Navigate to https://demo.prestashop.com/
**Steps to reproduce**
1. Click on the "Sing in" item
2.Click on the "No account? Create one here"
3. Check "Mrs" radio button.
4. Insert "test" in First name field and Last name field.
6. Insert * 123456@2345" in Email field and " teste' in password field.
7. Blank "Birthdate"
8. Check all check-boxes.
9. Press "Save" button
**Expected results**: The new account must be created with valid data and a successfully notification is visible.
**Actual results**: The new account can be created with invalid data and successfully notification is missing.
**Occurrance**: Systematic
**Severity**: High
**Priority**: Medium
**Module**: New account
**Browser**: Edge

-----------------

**Title** The site is not stable.

**Description**: The site is crashed when I connect in the account and Click twice on the back button.

**Precondition**: Navigate to https://demo.prestashop.com
**Steps to reproduce**: 
1. Click on the "Sing in item"
2. Login with email: 123456@2345 password: teste
3. Multiple Clicks on the Back button.

**Expected results**: The account page should be displayed.
**Actual results**: The page is crashed.
**Occurrence**: Systematic
**Severity**: Critic
**Priority**: Critic
**Module**: Login account
**Browser**: Edge.
**Attachments**
Drop files to attach, or browse.
Image 2022-12-2
Just now
133 kB

------------------


**Title**: Images are not displayed.

**Description**: The imagines of the products are not displayed.

**Steps to reproduce**:
1. Navigate on https://demo.prestashop.com/
2. Navigate on the page of the site.

**Expected results**: 
The imagine is displayed from each product.

**Actual results**: 
The imagine are not displayed from all products.

**Occurrence**: Systematic
**Additional info**:
This issue is reproduce in all pages and categories of the site.
**Severity**: Low
**Priority**: High
**Module**: Home page
**Browser**: Edge.
**Attachments**
Drop files to attach, or browse.
3.JPG
Just now
94 KB


------------------------


 **Title**:The page refused to connect at the server.
 
 **Description**: 
 The prestashop.com page refuse to connect at the server after a shipping order.
 
 **Steps to reproduce**: 
 1.Navigate to www.prestashop.com 
 2. Place an order.
 3. Let the page with successfully notification open aprox. 2 hours. 
 4. Click on the Back button.
 
 **Expected results**:
  The home page of the site is displayed. 
  
 **Actual results**: 
 The web site is not respond to the command.
** Occurrence**: 
 **Severity**: Critic 
 **Priority**: Critic 
** Browser**: Edge 
 **Module**: Order.
