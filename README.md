# auth2

## Description
Registration & Authentication using bcrypt and Passport

## Tech Stack
- Express
- Passport
- bcrypt
- Jade
- MySQL


## Paths

Use the below paths to test this program
- /users/register - to register a new user
- /users/signin - to signin
- /protected - page will display if signed-in. Otherwise will redirect to login page
- /logout - redirects to home '/'

The below paths are used by the app
- /success - indicates the login has succeeded
- /fail - indicates the login has failed

## Database

The app uses a MySQL db named db_users with one table named tbl_users.
Use db_users.sql to create the table.

## Partially based on
[NodeJS Passport login script with MySQL database](https://programmerblog.net/nodejs-passport-login-mysql/)
