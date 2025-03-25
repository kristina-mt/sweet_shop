# Sweet Shop Website - Test Scenarios with Steps

| Module                     | Test Case ID | Test Description                                                             | Steps to Test                                                                                |
| -------------------------- | ------------ | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| About Page                 | 1.1          | Check the page has title 'Sweet Shop Project'                                | Open the About page and check the browser title is   ---------------------------------------------------------------------------------------------------------------------------|'Sweet Shop Project'. 
|
|
| About Page                 | 1.2          | Check the page has the description                                           | Scroll through the About page and verify the project ---------------------------------------------------------------------------------------------------------------------------|description is present and readable. 
|
|
| About Page                 | 1.3          | Check the page has the banner and it matches 2018                            | Verify that the banner image is visible and contains ---------------------------------------------------------------------------------------------------------------------------|the text or visual style from 2018.
|
|
| About Page                 | 1.4          | Check the presence of team or contact info                                   | Look for team/contact section and verify it contains ---------------------------------------------------------------------------------------------------------------------------| names, emails or links (if applicable). 
|
|
| About Page                 | 1.5          | Check if images or links on the page are rendering and functioning correctly | Ensure all images are loaded correctly and links ---------------------------------------------------------------------------------------------------------------------------|navigate to expected locations. 
|
|
| About Page                 | 1.6          | Check for spelling/grammar consistency in the description and headings       | Read all visible text and verify there are no typos ---------------------------------------------------------------------------------------------------------------------------| or grammatical errors.  
|
|
| About Page                 | 1.7          | Check responsiveness of the page on various screen sizes                     | Resize the browser or view on mobile/tablet and ---------------------------------------------------------------------------------------------------------------------------| confirm layout adjusts properly.  
|
|
| About Page                 | 1.8          | Check accessibility features (contrast, alt tags, etc.)                      | Use accessibility tools (e.g. screen reader, contrast ---------------------------------------------------------------------------------------------------------------------------| checker) to verify compliance.    

|     |
| Login Page - Page Load     | 2.1.1        | Check 'Login' title and description                                          | Open the login page and confirm the title is 'Login' and there's a brief description.        |
| Login Page - Page Load     | 2.1.2        | Check the page has 'username' and 'password' textboxes                       | Ensure that username and password input fields are visible and interactable.                 |
| Login Page - Functionality | 2.2.1        | Successful login scenario                                                    | Enter valid credentials and submit. Confirm you are logged in and redirected.                |
| Login Page - Functionality | 2.2.2        | Unsuccessful login scenario                                                  | Enter invalid credentials and verify an error message is displayed.                          |
| Login Page - UI/UX         | 2.3.1        | Check presence and visibility of 'Login' button                              | Verify that the 'Login' button is visible and enabled by default.                            |
| Login Page - UI/UX         | 2.3.2        | Check if 'Forgot Password?' link exists and works                            | Look for 'Forgot Password' and click to ensure it leads to a reset flow or message.          |
| Login Page - UI/UX         | 2.3.3        | Check if password field hides input (masking)                                | Type a password and confirm it is masked (hidden).                                           |
| Login Page - UI/UX         | 2.3.4        | Check for 'Show Password' toggle (if applicable)                             | Check if a 'show password' icon is present and toggles visibility.                           |
| Login Page - UI/UX         | 2.3.5        | Check if tab order is correct                                                | Use the Tab key to navigate in logical order through input and button.                       |
| Login Page - UI/UX         | 2.3.6        | Check for accessibility features                                             | Inspect the DOM to ensure labels/aria tags are present for accessibility.                    |
| Login Page - Validation    | 2.4.1        | Check error messages for missing username or password                        | Leave both fields empty and try logging in — ensure error is shown.                          |
| Login Page - Validation    | 2.4.2        | Check error when entering only one field                                     | Enter only username or only password — ensure specific error is shown.                       |
| Login Page - Validation    | 2.4.3        | Check validation for input with only whitespace                              | Try entering only spaces and verify that validation prevents submission.                     |
| Login Page - Validation    | 2.4.4        | Check for error on incorrect credentials                                     | Use incorrect credentials and confirm a general error message appears.                       |
| Login Page - Validation    | 2.4.5        | Check input length constraints                                               | Enter an overly long username/password and check validation limits.                          |
| Login Page - Validation    | 2.4.6        | Check special characters are handled properly                                | Enter HTML/JS (e.g. <script>) and ensure it's not executed.                                  |
| Login Page - Validation    | 2.4.7        | Check SQL injection is blocked                                               | Try common SQL injection strings and verify they’re blocked or neutralized.                  |
| Login Page - Post Login    | 2.5.1        | Check user is redirected after successful login                              | Login successfully and confirm redirection to dashboard/homepage.                            |
| Login Page - Post Login    | 2.5.2        | Check a session token/cookie is created                                      | Check developer tools → Application → Cookies to verify a session is stored.                 |
| Login Page - Post Login    | 2.5.3        | Check for proper UI feedback                                                 | Look for greeting or UI update indicating successful login.                                  |
| Login Page - Post Login    | 2.5.4        | Check 'Back' button behavior after login                                     | After login, press the Back button and verify you're not returned to the login page.         |
| Login Page - Security      | 2.6.1        | Check if login page uses HTTPS                                               | Look at the URL — confirm it's https:// not http://                                          |
| Login Page - Security      | 2.6.2        | Check brute-force prevention mechanisms                                      | Attempt multiple failed logins — check for rate-limiting or CAPTCHA.                         |
| Login Page - Security      | 2.6.3        | Check for generic error messages                                             | Confirm errors don’t reveal if username or password is incorrect.                            |
| Login Page - Security      | 2.6.4        | Check session timeout behavior                                               | Remain idle after login and check if auto-logout occurs after timeout.                       |
| Login Page - Security      | 2.6.5        | Check CSRF protection                                                        | Use dev tools to look for CSRF tokens on form submit (or confirm behavior).                  |
| Login Page - Security      | 2.6.6        | Check credentials are not stored in localStorage or exposed in JS            | Inspect localStorage/sessionStorage — ensure no passwords or sensitive data stored.          |
