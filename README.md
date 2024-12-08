# Basic E-Commerce Application

A basic e-commerce application built using the MERN stack.

## Features

- User authentication and authorization
- Product management (CRUD operations)
- MongoDB database integration
- RESTful API with Express.js
- Environment variables with dotenv
- Error handling and validation

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/basic-ecom.git
   ```
2. Navigate to the project directory:
   ```sh
   cd basic-ecom
   ```
3. Install dependencies for both backend and frontend:
   ```sh
   npm install
   ```

## Usage

1. Create a `.env` file in the root directory and add your MongoDB URI and other environment variables:
   ```env
   MONGO_URI=your_mongodb_uri
   PORT=5000
   ```
2. Start the development server:
   ```sh
   npm run dev
   ```

## API Endpoints

- `GET /api/products` - Retrieve all products
- `POST /api/products` - Create a new product
- `PUT /api/products/:id` - Update an existing product
- `DELETE /api/products/:id` - Delete a product

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.
