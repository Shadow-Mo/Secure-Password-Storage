# Secure Password Storage

This is a simple demonstration of a secure password storage system using client-side hashing (SHA-256). Originally, the project used PHP for server-side password hashing, but to make it accessible on GitHub Pages without a server, I had to switch to client-side JavaScript for password hashing.

## Features

- User registration with client-side password hashing
- User login with verification against hashed passwords
- Secure password storage using local storage
- Simple UI with background image fetched from Unsplash API

## Demo

You can access the live demo of this project on GitHub Pages: [Secure Password Storage Demo](https://shadow-mo.github.io/Secure-Password-Storage/register.html)

## Installation and Usage

1. Clone the repository:

git clone https://github.com/Shadow-Mo/Secure-Password-Storage.git

2. Open the `register.html` file in your web browser.

3. Use the provided registration form to create a new user account.

4. Use the login form to log in with the registered credentials.

## Technologies Used

- HTML
- CSS (Tailwind CSS)
- JavaScript

## Credits

- Background image sourced from [Unsplash](https://unsplash.com/)
- Argon2 password hashing library provided by [npm](https://www.npmjs.com/package/argon2)

## Acknowledgments

Special thanks to Unsplash for providing the background image. Also, thanks to the Argon2 library and the open-source community for enabling secure client-side password hashing.
