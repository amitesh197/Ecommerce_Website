# Shopping E-commerce Website

## Tech Stack

### Frontend
- **React.js**: A JavaScript library for building user interfaces.
- **Redux**: State management for React.
- **Material-UI**: React components for faster and easier web development.
- **TailwindCSS**: A utility-first CSS framework.
- **React Hooks**: Functions that let you use state and other React features without writing a class.

### Backend
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing application data.
- **jsonwebtoken**: For token-based authentication.

## Features
- **Cart and Checkout**: Add products to the cart and proceed to checkout.
- **Place Order**: Complete the purchase by placing an order.
- **User Authentication**: Signup, login, and secure access to the user-specific features.
- **Product Search and Filter**: Search for products and apply filters to refine the results.
- **Add Product to Favorite List**: Save products to a favorites list for future reference.
- **Home Page**: Overview of the website with featured products and categories.
- **Products List Page**: Browse all available products.
- **Cart Page**: View and manage the products in the cart.
- **Signin and Register Page**: Create a new account or log in to an existing one.

## Home Page - 
![Screenshot 2024-06-13 222235](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/2b67ce01-9da0-4150-b8cd-726cfc40b67a)
![Screenshot 2024-06-13 225507](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/daa70f28-7357-4079-82ee-f31bb74662fc)

## Products List Page - 
![Screenshot 2024-06-13 225549](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/4893a59f-1c7b-4eac-8766-a155ea81613c)

## Single Product Page - 
![Screenshot 2024-06-13 225615](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/bcc78b74-7208-49a5-81df-0f78c375741e)

## Cart - 
![Screenshot 2024-06-13 225716](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/9b8b3659-2950-4671-94b8-407f69e24e4d)

## Signin Page - 
![Screenshot 2024-06-13 230054](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/decf72de-aad1-41ad-9a9b-9fce6881f35a)

## Register Page - 
![Screenshot 2024-06-13 230109](https://github.com/amitesh197/Ecommerce_Website/assets/123076729/9ba5813c-4baf-41d5-a5c1-74ceb1f29a4e)


## Installation and Setup

### Environment Variables
Create a `.env` file in the `server` directory with the following content:

```
MONGO_DB = <your_mongodb_connection_string>
JWT = <your_jwt_secret_key>
```

### Server Setup
1. Navigate to the `server` directory:
   ```bash
   cd server
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```

### Client Setup
1. Navigate to the `client` directory:
   ```bash
   cd client
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the client:
   ```bash
   npm start
   ```

## Usage
Once both the server and client are running, you can access the website by navigating to `http://localhost:3000` in your browser.
