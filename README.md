

---

# ShopEZ

ShopEZ is a full-stack eCommerce website built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This project enables users to explore and shop for a variety of products, with a focus on smooth, user-friendly navigation, secure transactions, and modern design.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview

shoEZ is an online marketplace designed for footwear enthusiasts. It allows users to browse, search, and filter products by category, view product details, add items to the cart, and securely check out. The project utilizes the MERN stack for a responsive and dynamic application experience.

## Features

- **Product Listings**: View a list of products with details like price, description, and images.
- **User Authentication**: Register and log in securely using JWT.
- **Shopping Cart**: Add products to the cart, update quantities, and view total prices.
- **Order Management**: Place orders, and track order status.
- **Admin Panel**: Admin can add/edit/remove products and manage user orders.
- **Responsive Design**: Accessible and fully responsive on various screen sizes.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/shoEZ.git
    cd shoEZ
    ```

2. **Install dependencies** for both server and client:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Create a `.env` file** in the server directory and add the following variables:
    ```plaintext
    MONGO_URI=your-mongodb-connection-string
    SECRET_KEY=your-jwt-secret
    ```

4. **Start the Development Servers**:
    - **Server**: 
        ```bash
        npm run start
        ```
    - **Client**:
        ```bash
        cd client
        npm start
        ```

## Usage

1. Open the application in your browser at `http://localhost:3000`.
2. Register or log in as a user.
3. Browse products, add items to the cart, and proceed to checkout.

For admin functionalities, log in with an admin account to access the admin panel.

## Technologies Used

- **Frontend**: React.js, Redux, CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT
- **API**: RESTful API for CRUD operations

## Contributing

Contributions are welcome! Please fork the repository and create a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Here's a "Contact" section to add to your README:

---

## Contact

For any questions, feedback, or inquiries, feel free to reach out:

Feel free to open an issue if you encounter any bugs or have suggestions to improve the project

---
