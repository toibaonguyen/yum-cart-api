# Yum Cart API

Yum Cart API is a backend service for an online food ordering and delivery platform. It provides a robust set of APIs to manage user accounts, menu items, orders, and real-time order tracking.

## Features

### User Management
- User registration and login.
- Role-based access control (Admin, Customer, Delivery Personnel).
- Secure authentication using JWT.

### Menu Management
- Add, update, delete, and view menu items.
- Categorize dishes (e.g., appetizers, main course, desserts).
- Support for uploading dish images.

### Cart Management
- Add items to the cart.
- Update quantities of items in the cart.
- Calculate total price with taxes.

### Order Management
- Place orders from the cart.
- Real-time order status updates (e.g., preparing, out for delivery, delivered).
- View order history.

### Payment Integration
- Secure payment processing using Stripe or PayPal.
- Generate invoices for completed orders.

### Delivery Management
- Integration with Google Maps API for tracking delivery locations.
- Assign orders to delivery personnel.

### Admin Dashboard
- Manage menu items and categories.
- View all orders and their statuses.
- Monitor inventory levels.

## Tech Stack
- **Backend Framework:** Spring Boot
- **Database:** MySQL
- **Caching:** Redis
- **Real-time Communication:** WebSocket
- **Cloud Storage:** AWS S3 (for images)
- **Containerization:** Docker

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with detailed explanations of your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
