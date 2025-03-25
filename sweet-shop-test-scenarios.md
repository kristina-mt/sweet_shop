# Sweet Shop Website - Test Scenarios

| Module                     | Test Case ID | Test Description                                                  |
|-------------------------   |--------------|-------------------------------------------------------------------|
| About Page                 | 1.1          | Check the page has title 'Sweet Shop Project'                     |
| About Page                 | 1.2          | Check the page has the description                                |
| About Page                 | 1.3          | Check the page has the banner and it matches 2018                 |
| About Page                 | 1.4          | Check the presence of team or contact info                        |
| About Page                 | 1.5          | Check if images or links on the page are rendering properly       |
| About Page                 | 1.6          | Check for spelling/grammar consistency                            |
| About Page                 | 1.7          | Check responsiveness on various screen sizes                      |
| About Page                 | 1.8          | Check accessibility features (contrast, alt tags, etc.)           |
| Login Page - Page Load     | 2.1.1        | Check 'Login' title and description                               |
| Login Page - Page Load     | 2.1.2        | Check the page has 'username' and 'password' textboxes            |
| Login Page - Functionality | 2.2.1        | Successful login scenario                                         |
| Login Page - Functionality | 2.2.2        | Unsuccessful login scenario                                       |
| Login Page - UI/UX         | 2.3.1        | Check presence and visibility of 'Login' button                   |
| Login Page - UI/UX         | 2.3.2        | Check if 'Forgot Password?' link exists and works                 |
| Login Page - UI/UX         | 2.3.3        | Check if password field hides input (masking)                     |
| Login Page - UI/UX         | 2.3.4        | Check for 'Show Password' toggle (if applicable)                  |
| Login Page - UI/UX         | 2.3.5        | Check if tab order is correct                                     |
| Login Page - UI/UX         | 2.3.6        | Check for accessibility features                                  |
| Login Page - Validation    | 2.4.1        | Check error messages for missing username or password             |
| Login Page - Validation    | 2.4.2        | Check error when entering only one field                          |
| Login Page - Validation    | 2.4.3        | Check validation for input with only whitespace                   |
| Login Page - Validation    | 2.4.4        | Check for error on incorrect credentials                          |
| Login Page - Validation    | 2.4.5        | Check input length constraints                                    |
| Login Page - Validation    | 2.4.6        | Check special characters are handled properly                     |
| Login Page - Validation    | 2.4.7        | Check SQL injection is blocked                                    |
| Login Page - Post Login    | 2.5.1        | Check user is redirected after successful login                   |
| Login Page - Post Login    | 2.5.2        | Check a session token/cookie is created                           |
| Login Page - Post Login    | 2.5.3        | Check for proper UI feedback                                      |
| Login Page - Post Login    | 2.5.4        | Check 'Back' button behavior after login                          |
| Login Page - Security      | 2.6.1        | Check if login page uses HTTPS                                    |
| Login Page - Security      | 2.6.2        | Check brute-force prevention mechanisms                           |
| Login Page - Security      | 2.6.3        | Check for generic error messages                                  |
| Login Page - Security      | 2.6.4        | Check session timeout behavior                                    |
| Login Page - Security      | 2.6.5        | Check CSRF protection                                             |
| Login Page - Security      | 2.6.6        | Check credentials are not stored in localStorage or exposed in JS |
