Flask Market App 💼
Welcome to the Flask Market App repository! This project showcases a web application built with Flask, simulating a marketplace where users can register, log in, and buy or sell items. The app uses Flask for routing, SQLAlchemy for database management, Flask-Login for user authentication, and Jinja2 for templating.

🌟 What's Inside?
Features of the Application ⚙️

1. User Registration & Authentication 🚪
- Users can create accounts, log in, and securely log out.
- Passwords are hashed for security, and login functionality includes checks for correct credentials.

2. Item Marketplace 🛍️
- Registered users can buy items if they have enough balance.
- Users can sell items they own back to the market.
- Flash messages provide instant feedback for successful or failed transactions.

3. Data Persistence 💾
- Uses SQLAlchemy for managing user and item data, allowing for smooth integration with a SQLite database.
- Full CRUD functionality for items and users.
  
4. Pages & Routes 🛤️
- Home Page: Basic landing page for the application.
- Market Page: The core marketplace where users can buy and sell items, available only after login.
- Register Page: Page where new users can create an account.
- Login Page: Login form for existing users.
- Logout: Logs the user out and redirects to the home page.

5. Core Functionality 🔍
- User Registration: Users fill out a form with username, email, and password, which is then validated and saved in the database.
- Login/Logout: Users log in securely, and Flask-Login manages session cookies.
- Buying & Selling: Users can purchase items if they have sufficient funds and sell items back to the market.
  
6. Forms Used 📝
- RegisterForm: Handles user registration inputs (username, email, password).
- LoginForm: Manages user login.
- PurchaseItemForm: Form used for purchasing items in the marketplace.
- SellItemForm: Form used for selling items.
