# Pizza Ordering App

This is a simple web application that allows users to order pizzas from a menu without the need for user accounts or login. Users can easily input their names before using the app and add multiple pizzas to a cart before placing an order. The app leverages modern web technologies such as React, Vite, React Router, tailwindcss, and Redux to provide a smooth and intuitive user experience.

## Preview

![Website Screenshot](https://fast-react-pizza.vercel.app/app.png)

## Features

- **User-Friendly Interface**: The application offers a straightforward and intuitive interface, allowing users to order pizzas easily.
- **Dynamic Pizza Menu**: The pizza menu is loaded from an API, enabling the flexibility to change the available options and prices.
- **Cart Functionality**: Users can add multiple pizzas to a cart before finalizing their order.
- **Order Placement**: Ordering requires providing the user's name, phone number, address, and optional GPS location for convenient delivery.
- **Priority Order**: Users have the option to mark their order as a "priority" order, incurring an additional 20% cost on the cart price.
- **Order Submission**: Orders are made by sending a POST request with the order data, including user information and selected pizzas, to the API.
- **Payment on Delivery**: Payments are handled during delivery, eliminating the need for payment processing within the app.
- **Order Tracking**: Each order receives a unique ID, allowing users to later look up their order status using the provided ID.
- **Order Modification**: Users can mark an existing order as a "priority" order even after it has been placed.

## Technologies Used

- React: A popular JavaScript library for building user interfaces.
- Vite: A fast and efficient build tool for modern web applications.
- React Router: A routing library for React applications, enabling navigation between different views. data fetching with React Router `Loaders`
- tailwindcss: A utility-first CSS framework for quickly building responsive and customizable interfaces.
- Redux: A predictable state container for JavaScript applications, providing centralized state management.

## Getting Started

To set up the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/makkianjum/fast-react-pizza.git`.
2. Navigate to the project directory: `cd your-repo`.
3. Install the dependencies: `npm install` or `yarn install`.
4. Start the development server: `npm run dev` or `yarn dev`.
5. Open your browser and visit `http://localhost:5173` to access the application.
