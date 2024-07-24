# API E-commerce

API for e-commerce using Flask: Manage products and authenticate users with functionalities for login, registration, and shopping cart. Includes endpoints to add, update, and delete products, as well as handling the cart and checkout process. Integrated with Flask-Login and SQLAlchemy.

## Features

- **User Authentication**: Register, login, and manage user sessions.
- **Product Management**: Add, update, delete, and view products.
- **Shopping Cart**: Add items to the cart, update quantities, and remove items.
- **Checkout**: Handle the checkout process and order completion.

## Technologies Used

- **Flask**: Web framework
- **SQLAlchemy**: ORM for database management
- **Flask-Login**: User session management
- **SQLite**: Database

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/felipexavier14/api-e-commerce.git
    ```
2. Navigate to the project directory:
    ```bash
    cd api-e-commerce
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```
5. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    flask run
    ```
2. The API will be available at `http://127.0.0.1:5000`.

## Endpoints

- **User Endpoints**:
  - `POST /register`: Register a new user.
  - `POST /login`: Login a user.
  - `GET /logout`: Logout the current user.

- **Product Endpoints**:
  - `GET /products`: Get all products.
  - `POST /products`: Add a new product.
  - `PUT /products/<id>`: Update a product.
  - `DELETE /products/<id>`: Delete a product.

- **Cart Endpoints**:
  - `GET /cart`: Get the current user's cart.
  - `POST /cart`: Add an item to the cart.
  - `PUT /cart/<id>`: Update item quantity in the cart.
  - `DELETE /cart/<id>`: Remove an item from the cart.

- **Checkout Endpoint**:
  - `POST /checkout`: Complete the checkout process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Felipe C Xavier**
  - [LinkedIn](https://www.linkedin.com/in/felipexavier14)
  - [GitHub](https://github.com/felipexavier14)

Feel free to explore, use, and contribute to this project. Thank you for checking out my API!
