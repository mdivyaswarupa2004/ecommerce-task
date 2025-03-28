# **E-Commerce Marketplace**

## **About the Project**

This is an E-Commerce web application where users can browse and buy products online. Sellers can list their products, and buyers can add them to the cart, purchase them, and track their orders. The application provides a smooth and secure shopping experience.

## **Features**

Homepage – Shows all available products and a search bar to find specific items.

Add to Cart & Wishlist – Users can save products for later or add them directly to their cart.

Checkout – Secure payment process and order confirmation.

My Orders – Users can view their past orders and track deliveries.

User Profile – Users can manage their personal information and order history.

## **Tech Stack Used**

This project is built using the following technologies:

React.js -> Frontend (User Interface)

Node.js -> Backend (Server-Side Logic)

Express.js -> API Development

MySQL -> Database for storing users, products, and orders

Git & GitHub -> Version Control & Collaboration

## **Prerequisites**

Before you begin, ensure you have the following installed:

Node.js (v14.0.0 )

npm (v6.0.0 ) -> Comes with Node.js

MySQL Server

## **Installation & Setup**

 Clone the Repository
    git clone <https://github.com/mdivyaswarupa/ecommerce.git>

    cd ecommerce

Install Dependencies

Backend:

    'cd backend'

    'npm install'

Frontend:

    'cd ../frontend'

    'npm install'

Database Configuration

1. Create a MySQL database named ecommerce.

2. Configure the database connection in backend/config/database.js.

3. Update the .env file with your database credentials:

     DB_HOST=localhost

    DB_USER=your_username

    DB_PASSWORD=your_password

    DB_NAME=ecommerce

## **Project Structure**

    ecommerce-store/

    │─ backend/         
    │─ frontend/       
    │─ database/       
    │─ public/          # Static files like images, CSS
    │─ .env             # Environment variables
    │─ package.json     # Dependencies and project info
    │─ README.md        # Project documentation

## **Note**

1. Create a new branch for each feature.

2. Use descriptive branch names like feature/add-wishlist , bugfix/cart-calculation

3. Commit Message Conventions:
Use clear and concise commit messages:
feat: Add wishlist functionality
fix: Resolve checkout page loading issue
docs: Update README with setup instructions
Troubleshooting
Ensure all dependencies are correctly installed.
Check database connection settings.
Verify .env file configurations.

## *License*

This project is licensed under the MIT License. You are free to use and modify it, but it comes with no warranty.
