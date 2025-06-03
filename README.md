# Amazon Clone using MERN Stack

## Overview
This project is a fully functional e-commerce web application inspired by Amazon, built using the Java, SpringBoot,React,HMTL3,CSS stack. It includes essential features like user authentication, product management, shopping cart, order processing, and payment integration.

## Features
- **User Authentication**: Signup, login, logout, and profile management.
- **Admin Dashboard**: Manage products, users, and orders.
- **Product Management**: Add, update, and delete products.
- **Shopping Cart**: Add/remove products, view cart details.
- **Order Processing**: Checkout, order history, and status tracking.
- **Payment Integration**: Secure payment processing.
- **Reviews & Ratings**: Users can review and rate products.
- **Responsive Design**: Works seamlessly across devices.

## Tech Stack
- **Frontend**: React, Redux, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ORM)
- **Authentication**: JWT (JSON Web Tokens)
- **Payment**: Stripe/PayPal integration

## Installation & Setup
### Prerequisites
- Node.js (Latest LTS version)
- MongoDB (Local or cloud-based)
- npm or yarn

### Clone the Repository
```sh
git clone https://github.com/your-username/amazon-clone.git
cd amazon-clone
```

### Backend Setup
1. Navigate to the backend directory:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and configure the following environment variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   STRIPE_SECRET=your_stripe_secret_key
   ```
4. Start the backend server:
   ```sh
   npm run dev
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React application:
   ```sh
   npm start
   ```

### Running the Application
After starting both the frontend and backend servers, open your browser and visit:
```
http://localhost:3000
```

## API Endpoints
### User Routes
- `POST /api/users/login` - Authenticate user
- `POST /api/users/register` - Register a new user
- `GET /api/users/profile` - Get user profile (Protected)

### Product Routes
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get a single product
- `POST /api/products` - Create a new product (Admin only)

### Order Routes
- `POST /api/orders` - Create a new order
- `GET /api/orders/:id` - Get order details
- `GET /api/orders/myorders` - Get user orders

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Open a pull request

## License
This project is open-source and available under the MIT License.

## Contact
For any inquiries, feel free to reach out via [GitHub Issues](https://github.com/your-username/amazon-clone/issues).

