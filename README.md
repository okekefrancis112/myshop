# MyShop

A Django e-commerce application with shopping cart functionality, order management, and product catalog.

## Overview

A full-featured online shop built with Django featuring product browsing, cart management, and checkout flow.

## Features

- **Product Catalog** — Browse products by category
- **Shopping Cart** — Add, update, remove items with session-based cart
- **Order Management** — Place and track orders
- **Coupons** — Discount coupon system
- **Context Processors** — Cart accessible across all templates

## Tech Stack

- **Python** 3.9
- **Django** — Web framework
- **Pipenv** — Dependency management
- **SQLite** — Database

## Getting Started

```bash
git clone https://github.com/okekefrancis112/myshop.git
cd myshop/m
pipenv install
pipenv shell
cd myshop
python manage.py migrate
python manage.py runserver
```

## Project Structure

```
└── m/myshop/
    ├── cart/
    │   ├── cart.py              # Cart logic
    │   ├── views.py             # Cart views
    │   ├── forms.py             # Cart forms
    │   └── context_processors.py
    ├── orders/                  # Order management
    ├── shop/                    # Product catalog
    ├── coupons/                 # Coupon system
    └── manage.py
```

## License

MIT
