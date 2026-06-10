# Login Test Cases

| Test Case ID | Test Scenario                          | Preconditions            | Test Steps                                              | Test Data                     | Expected Result                                                        |
| ------------ | -------------------------------------- | ------------------------ | ------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------- |
| TC_LOGIN_001 | Login with valid credentials           | User account exists      | Enter valid username and password. Click Login.         | valid_user / valid_password   | User should be logged in successfully and redirected to the home page. |
| TC_LOGIN_002 | Login with invalid password            | User account exists      | Enter valid username and invalid password. Click Login. | valid_user / invalid_password | Appropriate error message should be displayed.                         |
| TC_LOGIN_003 | Login with invalid username            | Login page is accessible | Enter invalid username and valid password. Click Login. | invalid_user / valid_password | Appropriate error message should be displayed.                         |
| TC_LOGIN_004 | Login with blank username and password | Login page is accessible | Leave username and password fields blank. Click Login.  | Blank values                  | Validation message should be displayed.                                |
| TC_LOGIN_005 | Verify Forgot Password functionality   | Login page is accessible | Click Forgot Password link.                             | N/A                           | User should be redirected to the Forgot Password page.                 |
