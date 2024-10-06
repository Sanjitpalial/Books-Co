# Books & Co. 📚

Books & Co. is a full-featured e-commerce website for book lovers, allowing users to browse, search, and purchase books. Built with a Django backend and HTML/CSS/JavaScript for the frontend, this platform provides a smooth user experience for discovering and buying books online.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Book Search & Browse**: Search books by title, author, or genre.
- **Personalized Recommendations**: Users receive recommendations based on their preferences.
- **User Reviews & Ratings**: Read and write reviews for books.
- **Wishlist & Cart**: Users can add books to a wishlist or shopping cart.
- **Order Tracking**: Track orders and view purchase history.
- **Admin Dashboard**: Admins can manage books, inventory, and orders.
- **Secure Checkout**: Integrated with secure payment methods.

---

## Screenshots

Here are some screenshots to help visualize the features of Books & Co.

### Home Page

![Home Page](C:\Users\sanji\OneDrive\Pictures\Screenshots\Screenshot 2024-05-14 225608.png)

### Book Search

![Search Results](./screenshots/search-results.png)

### Book Details

![Book Details](./screenshots/book-details.png)

### Shopping Cart

![Shopping Cart](./screenshots/shopping-cart.png)

### Admin Dashboard

![Admin Dashboard](./screenshots/admin-dashboard.png)

---

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Django (Python)
- **Database**: SQLite (default), PostgreSQL/MySQL for production
- **Hosting**: AWS, Heroku, or any Django-compatible platform

---

## Getting Started

To set up the project locally, follow the steps below.

### Prerequisites

- Python 3.x
- Django 4.x
- SQLite (or PostgreSQL/MySQL for production)

---

## Environment Variables

Create a `.env` file in the root directory to manage environment variables:

```bash
SECRET_KEY=your_django_secret_key
DEBUG=True

# Database settings (if using PostgreSQL/MySQL in production)
DATABASE_URL=your_database_url

# Payment provider details (Stripe/PayPal or any local provider)
PAYMENT_API_KEY=your_payment_api_key
