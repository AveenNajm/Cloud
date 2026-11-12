# Cloud Computing- 2026 Workshop week 7 - 9 

The frontend pages (index.php, register.php, and success.php) interact with the backend processor (process_register.php), which stores user information in the Azure SQL Database (shopusers table).
# index.php – Home Page
This is the first page users see when they visit the website. It introduces MyShop and contains the "Create Your Account" button, which takes users to the registration page.
# register.php – Registration Form
This page displays the registration form where users enter their:
Full Name
Email Address
Password
When users click Register, the information is sent to process_register.php.
# process_register.php – Backend Processor
This is the application's backend logic. It receives data from the registration form, validates it, connects to the database, encrypts the password, and stores the user information in the shopusers table.
# success.php – Confirmation Page
After a successful registration, users are redirected to this page. It confirms that their account has been created successfully.
# config.php
Stores database connection settings such as:
Server name
Database name
Username
Password
This helps keep database settings in one place.
# display_users.php
Retrieves user information from the database and displays it on the webpage.
# add_users.php
Inserts new user records into the database. This is typically used for testing or demonstrations.
# styles.css 
Controls the website's appearance, including: Colours, Fonts, Layout, Buttons
# script.js
Adds interactive behaviour to the website using JavaScript.
Examples:
Button actions
Form validation
Dynamic updates
