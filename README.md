# 🛒 Django E-Commerce Store

A full-stack e-commerce web application developed using **Python and Django**. 
The project provides a simple online shopping experience with product 
browsing, user authentication, shopping cart functionality, and checkout.

## 🚀 Features

- 👤 User Registration and Login
- 🛍️ Product Listing
- 🔎 Product Details
- 🛒 Add Products to Cart
- ➕ Update Cart Items
- ➖ Remove Products from Cart
- 💳 Checkout Page
- 🖼️ Product Image Support
- 🗄️ SQLite Database
- 🔐 Django Authentication
- ⚙️ Django Admin Panel
- 📱 Template-based web interface

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Django | Web framework |
| SQLite | Database |
| HTML5 | Web structure |
| CSS3 | Styling |
| JavaScript | Client-side functionality |
| Pillow | Image processing |
| Git | Version control |
| GitHub | Source code hosting |

## 📂 Project Structure

```text
ecommerce/
│
├── ecommerce/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── store/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── signals.py
│   ├── tests.py
│   ├── utils.py
│   └── views.py
│
├── static/
│   ├── css/
│   │   └── main.css
│   ├── images/
│   └── js/
│       └── cart.js
│
├── templates/
│   └── store/
│       ├── main.html
│       ├── store.html
│       ├── product_detail.html
│       ├── cart.html
│       ├── checkout.html
│       ├── login.html
│       └── register.html
│
├── manage.py
├── requirements.txt
└── .gitignore