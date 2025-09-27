# ![alt text](logo2-1.png) Bréw Connect - E-Commerce Frontend

This is the frontend for a complete full-stack e-commerce web application for a fictional coffee brand. It features a modern, responsive user interface and connects to a custom-built backend API to manage products, users, and orders.

**Live Demo:** [https://coffee-leaf-frontend.vercel.app/](https://coffee-leaf-frontend.vercel.app/) 



---
## Features

* **Dynamic Product Catalog:** The menu page fetches and displays all coffee products directly from the backend API.
* **User Authentication:** Fully-featured user registration and login system. The navbar dynamically updates based on login status.
* **Persistent Shopping Cart:** A logged-in user's cart is saved to their database account and persists across devices.
* **Guest Cart:** Non-logged-in users can still shop using a cart stored in local storage.
* **Simulated Payment Flow:** A complete checkout process with options for **Card** and **Cash on Delivery** that simulates a real transaction.
* **Order History:** A dedicated profile page where logged-in users can view all their past orders.
* **Unique Mood Recommender:** A custom page that calls a special API endpoint to filter and suggest coffees based on user-selected moods.
* **Responsive Design:** The layout is fully responsive and works beautifully on devices of all sizes.
---

## Tech Stack

* **HTML5**
* **CSS3** (with Flexbox and Grid)
* **Vanilla JavaScript (ES6+)** (DOM Manipulation, Fetch API, Async/Await)

---

## Setup and Installation

To run this project locally:

1.  Clone the repository:
    ```bash
    git clone https://github.com/ishanijdev/coffee-leaf-frontend.git
    ```
2.  Open the `index.html` file in your browser (the VS Code "Live Server" extension is recommended).
3.  **Note:** This frontend requires the [backend server](https://github.com/ishanijdev/coffee-leaf-backend) to be running locally for API calls to work.

---

## License 

This project is open-source and free to use for educational purposes.