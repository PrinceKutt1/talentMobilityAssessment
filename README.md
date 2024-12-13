# talentMobilityAssessment
Backend API for a responsive product list with shopping cart functionality, focusing on API design, data management, and frontend integration.
# Dessert Shop Backend API

## Project Overview
This is a comprehensive backend API for a dessert shop application, supporting product management and shopping cart functionality.

## Features
- Full CRUD operations for products
- Shopping cart management
- Admin authentication
- Swagger API documentation
- MongoDB integration
- TypeScript support

## Prerequisites
- Node.js (v14+ recommended)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository
```bash
git clone https://your-repo-url.git
cd dessert-shop-api
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
- Copy `.env.example` to `.env`
- Update the configurations as needed

## Running the Application

### Development Mode
```bash
npm run dev
```

### Production Build
```bash
npm run build
npm start
```

## Testing
```bash
npm test
```

## API Documentation
Access Swagger UI at: `http://localhost:3000/api-docs`

## Authentication
- Admin login endpoint: `/login`
- Use provided admin credentials in `.env`
- Receive JWT token for admin operations

## Endpoints

### Products
- `GET /products`: List all products
- `GET /products/:id`: Get specific product
- `POST /products`: Add product (Admin)
- `PUT /products/:id`: Update product (Admin)
- `DELETE /products/:id`: Delete product (Admin)

### Cart
- `GET /cart`: View cart
- `POST /cart`: Add item to cart
- `PUT /cart/:id`: Update cart item
- `DELETE /cart/:id`: Remove item from cart

## Environment Variables
- `PORT`: Server port
- `MONGODB_URI`: MongoDB connection string
- `JWT_SECRET`: Secret for token generation
- `ADMIN_USERNAME`: Admin login username
- `ADMIN_PASSWORD`: Admin login password

## Technology Stack
- Express.js
- TypeScript
- Mongoose
- JWT Authentication
- Zod Validation
- Swagger Documentation
