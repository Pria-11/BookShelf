# BookShelf

A minimal MERN bookstore application with core features for browsing, ordering, and administration.

## Features

- **User Authentication**  
  Secure signup/login with JSON Web Tokens (JWT).

- **Product Catalog**  
  Browse, search, and paginate books; view detailed information.

- **Shopping Cart**  
  Add/update/remove items; real‑time total price calculation.

- **Checkout & Payments**  
  Multi‑step checkout with shipping address, payment method (PayPal), and order review.

- **Order Management**  
  Create orders, view order status, and order history.

- **Admin Dashboard**  
  - **Product CRUD**: Create, edit, delete books  
  - **User Management**: List, edit, and delete users  
  - **Order Overview**: View and manage all orders

- **Role‑Based Access Control**  
  Admin‑only routes protect management screens.

- **Responsive Design**  
  Mobile‑first layout built with React Bootstrap.

## Getting Started

1. **Clone the repo**  
   ```bash
   https://github.com/Pria-11/BookShelf.git
Install dependencies

bash
Copy
Edit
cd frontend && npm install
cd ../backend && npm install
Configure environment

Copy .env.example to .env in /backend

Set MongoDB URI, JWT secret, and PayPal client ID.

Run the app

bash
Copy
Edit
# Backend
npm run server

# Frontend
npm start
