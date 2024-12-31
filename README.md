# Online Food Ordering System

This project is a database-backed system that facilitates online food ordering for customers, allowing them to browse restaurants, add items to a shopping cart, and place orders. It includes features such as customer management, order tracking, discount applications, and restaurant recommendations.

---

## Project Overview
The Online Food Ordering System is built to simulate a real-world food delivery service. It manages customer profiles, restaurants, dishes, shopping carts, orders, and payments, ensuring a seamless food ordering experience.

### Key Assumptions:
1. The system stores information about customers, discounts, restaurants, dishes, and orders.
2. Customers can:
   - Create and update their profiles.
   - Browse restaurants by category.
   - Add dishes to a shopping cart and place orders.
3. Restaurants can be categorized into multiple cuisines.
4. Orders are tracked with status updates (in progress, delivered, or canceled).

---

## Features

1. **Customer Management**
   - Create a new customer with unique IDs and handle duplicates.
   - View customer profiles, order history, and spending in the last six months.

2. **Restaurant Search**
   - Search restaurants by category and view their details, including average review scores and wait times.

3. **Shopping Cart**
   - Add, view, and remove dishes in a shopping cart.
   - Compute the total cost, including discounts, taxes, and delivery fees.

4. **Order Management**
   - Place orders with detailed information, including delivery method, status, and payment method.
   - Update order statuses and notify customers of updates.

5. **Reviews**
   - Customers can leave reviews for restaurants, which update the restaurant's average score.

6. **Recommendations**
   - Generate restaurant recommendations based on customer order history and preferences.

7. **Advanced Search**
   - Search for restaurants based on multiple criteria, including category, review score, and proximity.

---

## Database Design

The database schema includes:
- **Customers**: Stores customer details (ID, name, address, credit, etc.).
- **Restaurants**: Contains restaurant information (ID, name, categories, status, etc.).
- **Dishes**: Each dish has a unique ID, name, price, and associated restaurant.
- **Orders**: Tracks orders with details like status, cost, and delivery method.
- **Payments**: Records payment details and methods.
- **Messages**: Stores customer notifications and messages.
- **Reviews**: Captures reviews with scores and comments.

---

