# google-easy-register-and-login-web-page

Secrets - Anonymous Sharing App

This is a web application where users can share their embarrassing moments anonymously, similar to a social network. It features a seamless authentication system allowing users to register and log in via their Google account or personal email.


Prerequisites
To run this project locally, you will need a PostgreSQL database and Google OAuth 2.0 credentials.


Create a .env file in the root directory and configure it as follows:

GOOGLE_CLIENT_ID="your_client_id"

GOOGLE_CLIENT_SECRET="your_client_secret"

SESSION_SECRET="your_session_secret_here"

PG_USER="postgres"

PG_HOST="localhost"

PG_DATABASE="your_database_name"

PG_PASSWORD="your_password"

PG_PORT="5432"


Installation & Setup
Once your .env file and SQL infrastructure are set up, open your terminal (e.g., Git Bash) and install the required dependencies:


Git Bash

npm i

nodemon index.js



Security Note

Email Registration: For extra security, passwords are encrypted using bcrypt (salted and hashed) before being stored in the database.
Google Authentication: If you log in via Google, the password field is safely defaulted to "google" in the database, as the actual authentication is securely handled by Google's OAuth service.



Here are some of the screenshots from the project:

<img width="1908" height="1078" alt="image" src="https://github.com/user-attachments/assets/efbb77d7-be85-4041-b17a-be9ebe14e742" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0d595f31-6183-40c4-87be-e1a38f6651e1" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/fc4a56f7-874f-42d9-a0f4-c29934c475b7" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/5ea0477f-3ae5-46b6-9ab4-e35196523cb8" />
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/cfa90c69-b060-4509-9917-f9b2d5f36d25" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c75f1370-4d4b-4cac-87bf-085c049a0abe" />


