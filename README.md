# Hello, Namaste 🙏, Welcome to My YouTube MERN E-commerce App!

Thank you for visiting this project! This app is a full-stack e-commerce platform built using the MERN stack. It allows users to browse products, add items to their cart, and proceed to checkout with payment processing. Feel free to explore the code, provide feedback, or contribute. 🚀

---

# YouTube MERN E-commerce App

## Overview

This is a MERN stack e-commerce application where users can:
- View and search for products.
- Add products to their cart.
- Checkout using Stripe for payment processing.
- Manage their user profile and view order history.

## Features

- **User Authentication:** Secure login and signup with JWT authentication.
- **Product Management:** Display, search, and filter products.
- **Shopping Cart:** Add, remove, and adjust quantities of products in the cart.
- **Payment Integration:** Secure payments using Stripe API.
- **Responsive Design:** A seamless shopping experience across all devices.

## Tech Stack

**Frontend:**
- React.js
- Redux (for state management)
- Tailwind CSS (for styling)

**Backend:**
- Node.js
- Express.js
- MongoDB (for the database)
- Stripe API (for payment processing)
- JWT (for authentication)

## Installation and Setup

1. **Clone the Repository:**
    ```bash
    git clone <repository-url>
    cd youtube-mern-ecommerce-app
    ```

2. **Backend Setup:**
    - Navigate to the `api` directory:
      ```bash
      cd api
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Create a `.env` file in the `api` directory and configure the following:
      ```env
      PORT=5000
      MONGO_URI=your-mongo-db-uri
      JWT_SECRET=your-jwt-secret
      STRIPE_SECRET_KEY=your-stripe-secret-key
      ```
    - Start the backend server:
      ```bash
      npm start
      ```

3. **Frontend Setup:**
    - Navigate to the `client` directory:
      ```bash
      cd ../client
      ```
    - Install frontend dependencies:
      ```bash
      npm install
      ```
    - Create a `.env` file in the `client` directory and configure the following:
      ```env
      REACT_APP_API_URL=http://localhost:5000/api
      ```
    - Run the frontend development server:
      ```bash
      npm start
      ```

4. **Access the Application:**
    - Open your browser and go to `http://localhost:3000` to start using the app.

## Usage

- Browse products and add them to your cart.
- Sign in or create an account to proceed to checkout.
- Complete payment using Stripe integration.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.
