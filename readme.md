<h1 align="center"> eCommerce website </h1>

This eCommerce website is built to provide users with an intuitive online shopping experience. Users can browse through various products, add them to their cart, and proceed to checkout. The website also includes features for managing products, orders, and user accounts.

## Features:

* User Authentication and Authorization: Users can sign up, log in, and manage their accounts securely. Authentication is handled using JWT tokens.

* Product Browsing and Searching: Users can browse through various products, filter by categories, and search for specific items.
* Product Details and Reviews: Detailed product information, including images, descriptions, and reviews, are displayed to users.
* Shopping Cart Functionality: Users can add products to their cart, update quantities, and remove items.
* Checkout Process: Users can proceed to checkout, enter shipping and payment information, and place orders.
* Order Management: Users can view their order history, track order status, and manage orders.
* User Account Management: Users can update their profile information, change passwords, and manage addresses.

## Technologies Used:

- Frontend:
  - React JS: For building the user interface and managing state.
  - Redux Toolkit: For state management, including actions, reducers, and middleware.
  - RTK Query: For efficient data fetching and caching.
  - TypeScript: For static typing and improved code maintainability.

- Backend:
  - Node JS: For server-side JavaScript runtime environment.
  - Express JS: For building RESTful APIs and handling HTTP requests.
  - MongoDB: As the database for storing product data, user information, and orders.

## Setup
To set up this project locally, follow these steps:

1. Clone the repository:

2. Install dependencies:
```bash
cd ecommerce-website
npm install
```

3. Start the server:
```bash
npm start
```

4. Configure environment variables:Create a .env file in the root of the project and add the necessary environment variables like MongoDB connection string, JWT secret, etc.

5. Database setup:Make sure MongoDB is installed and running. Set up the database and collections as per your requirements.

6. Run the application:Visit http://localhost:3000 in your browser to view the application.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

- Fork the project.
Create your feature branch (git checkout -b feature/YourFeature).
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature/YourFeature).
- Open a pull request.

## License
This project is licensed under the [MIT License](./LICENSE).