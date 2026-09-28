# 🛒 Flask E-commerce Application

A Flask-based e-commerce web application featuring user authentication, product browsing, search, shopping cart, wishlist, and order management. The application includes an admin interface for managing products, inventory, and order status, with Docker support and Gunicorn for deployment.

## 📌 Overview

This project is an Amazon-inspired online shopping platform developed using Python and Flask. It provides customers with an interface to browse products, search for goods, manage their shopping cart, and place orders.

The application also includes account registration and login, password reset functionality, and administrative features for managing the store.

## ✨ Features

### 👤 Customer Features

* **User Registration:** Create a new customer account.
* **User Login:** Sign in using email and password.
* **Password Reset:** Reset forgotten passwords.
* **Product Search:** Search for products available in the store.
* **Product Categories:** Browse products by category.
* **Shopping Cart:** Add products, update quantities, and remove items.
* **Wishlist:** Save products for later.
* **Order Placement:** Proceed to checkout and place orders.
* **Payment Gateway:** Payment functionality for the checkout process.

### 🛠️ Admin Features

* **Product Management:** Add, update, and manage shop products.
* **Stock Management:** Regulate product inventory and stock levels.
* **Order Management:** View and manage customer orders.
* **Order Status:** Update order status as orders are processed.

### 🚀 Application Features

* Flask-based web application
* Gunicorn WSGI server support
* Docker-based deployment
* Responsive e-commerce interface
* Organized application structure using Flask modules

## 🖥️ Application Screenshots

### 1. Home Page

The home page displays the navigation bar, product categories, promotional banners, and product listings.

### 2. Login Page

The login page allows registered customers to enter their email address and password to access their accounts.

### 3. Shopping Cart

The shopping cart displays selected products, quantities, prices, and an order summary, including the total amount.

## 🧰 Tech Stack

| Technology                   | Purpose                   |
| ---------------------------- | ------------------------- |
| Python                       | Backend programming       |
| Flask                        | Web application framework |
| HTML                         | Page structure            |
| CSS                          | Styling and layout        |
| JavaScript                   | Frontend interactions     |
| Jinja2                       | Dynamic HTML templates    |
| Gunicorn                     | Production WSGI server    |
| Docker                       | Containerization          |
| SQLite / Configured Database | Data storage              |

*Note: Confirm the actual database and frontend dependencies in the project configuration before publishing this table.*

## 📂 Project Structure

```text
Flask-Ecommerce-main/
│
├── instance/
├── media/
├── venv/
│
├── website/
│   ├── __pycache__/
│   ├── static/
│   ├── templates/
│   ├── __init__.py
│   ├── admin.py
│   ├── auth.py
│   ├── forms.py
│   ├── models.py
│   └── views.py
│
├── Dockerfile
├── LICENSE
├── main.py
├── README.md
└── requirements.txt
```

### 📁 Important Files

* `main.py` — Application entry point.
* `website/__init__.py` — Flask application setup.
* `website/auth.py` — Authentication routes and functionality.
* `website/views.py` — Main application views and routes.
* `website/admin.py` — Administrative functionality.
* `website/forms.py` — Form definitions and validation.
* `website/models.py` — Database models.
* `website/templates/` — HTML templates.
* `website/static/` — Static assets such as CSS, JavaScript, and images.
* `requirements.txt` — Python dependencies.
* `Dockerfile` — Docker image build configuration.

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have the following installed:

* Python 3.8 or compatible version
* pip
* Git (optional)
* Docker Desktop (for containerized deployment)



## 🔐 Authentication

The application provides customer account functionality, including:

* Registration
* Login
* Password reset
* Access to customer shopping features

Authentication and session behavior are implemented within the Flask application.

## 🛍️ Shopping Workflow

1. Open the home page.
2. Browse products or search for a specific item.
3. Select products to add to the shopping cart.
4. Adjust quantities or remove products.
5. Review the cart summary.
6. Proceed to checkout and place an order.
7. Use the configured payment functionality, if enabled.

## 🛠️ Admin Workflow

1. Sign in with an authorized administrator account.
2. Access the admin functionality.
3. Manage product listings.
4. Update stock levels.
5. Review customer orders.
6. Change order statuses as required.

## 📦 Dependencies

Project dependencies are listed in:

```text
requirements.txt
```

Install them using:

```bash
pip install -r requirements.txt
```

## 🔮 Future Improvements

* Improve responsive design across mobile and desktop.
* Add product reviews and ratings.
* Improve order tracking.
* Add detailed sales analytics for administrators.
* Strengthen application security and configuration management.
* Add automated tests for shopping and checkout workflows.

## 👨‍💻 Author

**Your Name**

Python | Flask | Web Development | Docker

## 📄 License

This project includes a `LICENSE` file. Refer to that file for the applicable license terms.
