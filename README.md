# Demo Features

This demo showcases out-of-the-box User Registration and Login with the Auth0 Platform, along with:
- *Account Linking*: If the user is already registered and then attempts to register an account with the same email, they will be asked to link the accounts.
- *Email Verification*: If the user's email address is not verified, the user sees a notification message.
- *Profile Photo Metadata*: If there is a custom picture set for the user's profile, via user_metadata, this will override the default picture attribute (using Auth0 Rules).
- *User Country*: During authentication, Auth0 will attempt to determine the user's country, based on their IP Address (using Auth0 Rules), and that value will be displayed in the user's profile.

# Deployment Instructions

1. Open a console and clone this repository: `git clone https://github.com/jekennedy/auth0-demo`
2. Change directory to the repository: `cd auth-demo`
3. Execute: `npm install | npm start` (for instructions on using NPM: https://www.npmjs.com/get-npm)
4. Visit the demo application: http://localhost:3000

# User Instructions

*Account Linking*: Simply click the Login / Signup button to begin a user journey. You can sign-up via Email / Password, and then sign-up again using a Google account (with the same email address) to see the Account Linking flow. 

*Social Login*: During initial login, you can choose to Sign-in with Google to bypass the manual sign-up flow. 
