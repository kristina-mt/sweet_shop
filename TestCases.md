About page:
    1.1. Check the page has title 'Sweet Shop Project'
    1.2. Check the page has the description
    1.3. Check the page has the banner and it matches 2018.
 
    Login page:
    2.1: Page load:
        2.1.1. Check 'Login' title, description
        2.1.2. Check the page has 'username' and 'password' textboxes.
    2.2. Login functionality:
        2.2.1 Successful scenario
        2.2.2 Unsuccessful scenario

        //Chat gpt 


About Page:
Content & UI: 1.4. Check the presence of team or contact info (if applicable).
1.5. Check if images or links on the page are rendering and functioning correctly.
1.6. Check for spelling/grammar consistency in the description and headings.
1.7. Check responsiveness of the page on various screen sizes (mobile, tablet, desktop).
1.8. Check accessibility (contrast ratio, alt tags for images, etc.).

Login Page:
2.3. UI/UX Elements:
2.3.1. Check presence and visibility of "Login" button.
2.3.2. Check if "Forgot Password?" link exists and works (or is intentionally omitted).
2.3.3. Check if password field hides input (password masking).
2.3.4. Check if there is a 'Show Password' toggle (if applicable).
2.3.5. Check if tab order is correct (tabbing from username → password → login).
2.3.6. Check for accessibility features (labels, aria tags, etc.).

2.4. Form Validation:
2.4.1. Check error messages for missing username or password.
2.4.2. Check for error message when entering only one field.
2.4.3. Check validation for input with only whitespace.
2.4.4. Check for error on entering incorrect credentials.
2.4.5. Check for input length constraints (min/max for username/password).
2.4.6. Check if special characters are handled properly (e.g. <script> should not execute).
2.4.7. Check if SQL injection attempts are blocked (e.g., ' OR '1'='1).

2.5. Successful Login:
2.5.1. Check user is redirected to the correct page after successful login.
2.5.2. Check a session token/cookie is created (if using auth).
2.5.3. Check proper UI feedback (e.g., success message, user name shown).
2.5.4. Check "Back" button doesn’t allow going back to login after login.

2.6. Security Checks:
2.6.1. Check if login page uses HTTPS (secure connection).
2.6.2. Check rate limiting or CAPTCHA for brute-force prevention (if implemented).
2.6.3. Check if error messages are generic (not revealing if username or password is wrong).
2.6.4. Check session timeout behavior (auto logout after inactivity).
2.6.5. Check CSRF protection (if applicable).
2.6.6. Check that credentials are not stored in localStorage or exposed in JS.

