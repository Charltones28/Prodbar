# Product Store

## Description
The Product Store is a web application that allows vendors to create, update, and delete products. It leverages the MERN stack to provide a user-friendly and engaging interface for managing product listings. This project is part of my learning journey in building full-stack applications using the MERN stack.

## Project Status
This project is currently under active development. Features and structure may change as work progresses. Contributions and feedback are welcome!

## Technologies Used
- **Backend**: Node.js, Express.js
- **Frontend**: React
- **Database**: MongoDB

## Features
- Vendor product creation.
- Vendor product updates.
- Vendor product deletion.

## Installation

### Prerequisites
Ensure you have the following installed on your machine:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/charltones28/product-store.git
    ```
2. Navigate to the project directory:
    ```bash
    cd product-store
    ```
3. Install dependencies for the backend:
    ```bash
    cd backend
    npm install
    ```
4. Install dependencies for the frontend:
    ```bash
    cd ../frontend
    npm install
    ```
5. Create a `.env` file in the `backend` directory and add the necessary environment variables (e.g., database URI).
6. Start the backend server:
    ```bash
    cd backend
    npm start
    ```
7. Start the frontend development server:
    ```bash
    cd ../frontend
    npm start
    ```
8. Open your browser and navigate to `http://localhost:3000`.

## Usage
- Vendors can log in to the system and manage their products through an intuitive interface.
- The application allows vendors to add, edit, or remove product details seamlessly.

## Project Structure
```
backend/
  server.js          # Entry point for the backend
  routes/            # API routes
  models/            # MongoDB models
  controllers/       # Business logic

frontend/
  src/
    App.js          # Root component
    components/     # Reusable components
    pages/          # Page components (e.g., Home, Product Details)

config/               # Configuration files (e.g., database connection)
.env                  # Environment variables
```

## Future Enhancements
- Add authentication for vendors.
- Implement advanced search and filter features for products.
- Integrate analytics to track product performance.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions or feedback, feel free to contact me:
- **Name**: Charles Okon
- **Email**: charlesbiztraffick@gmail.com
- **GitHub**: [@charltones28](https://github.com/charltones28)
