# Software Test Plan – SauceDemo Manual Testing Project 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 1. Project Goal
The goal of this project is to test the main user flow of the SauceDemo web application.
The focus is on validating the core e-commerce process: login, product selection, cart management, and checkout completion.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 2. Scope of Testing

### Included
- Login and logout functionality
- Product list behavior and sorting
- Add and remove items from cart
- Full checkout flow (information → overview → finish)
- Basic input validation in forms


### Not Included
- Performance testing
- Security penetration testing
- Cross-browser compatibility testing
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 3. Testing Approach
Testing is performed manually using structured test cases.
The following types of testing are covered:
- Positive scenarios
- Negative scenarios
- Basic validation checks

A smoke test is executed before running the full test set.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 4. Test Environment
- Operating System: Windows 11
- Browser: Google Chrome (latest version)
- Application URL: https://www.saucedemo.com
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 5. Entry Criteria
- The application is accessible
- Test credentials are available
- No known blocking issues
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 6. Exit Criteria
- All planned test cases are executed
- Critical and high severity issues are reported
- Test summary report is completed
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 7. Risks and Limitations
Since this is a demo environment, there may be:
- Data resets between sessions
- Limited test user accounts
