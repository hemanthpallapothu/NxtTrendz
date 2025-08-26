# NxtTrendz

A secure, modern e-commerce platform built with React.js  
**Deployment:** [https://nxttrendsmall.ccbp.tech/login](https://nxttrendsmall.ccbp.tech/login)

---

## Project Description

NxtTrendz is a secure e-commerce web application, inspired by platforms like Amazon.  
It prioritizes security and a seamless user experience with:

- **JWT token-based user authentication**
- Modular React component architecture
- Dynamic product data handling via REST API
- Real-time cart management and checkout flow

> **Demo Credentials**
> - **Prime User**
> - **Username:** rahul  
> - **Password:** rahul@2021
> - **Non - Prime User**
> - **Username:** raja  
> - **Password:** raja@2021

---

## Component Structure

```
src/
├── App.js
├── components/
│   ├── Login/               
│   ├── Home/                
│   ├── Products/            
│   ├── ProductItemDetails/  
│   ├── Cart/               
│   ├── CartItem/            
│   ├── CartSummary/         
│   ├── Header/              
│   ├── ProtectedRoute/      
│   └── NotFound/            
└── context/
    └── CartContext.js       
``` 
---

## Component Breakdown

- **App.js**  
  _Sets up application routing and wraps the app in the cart context. Protected routes ensure security._

- **Login**  
  _Handles login via API, manages error states, and stores JWT token for secure session management._

- **Home**  
  _Displays a welcome message with primary site features for authenticated users._

- **Products**  
  _Fetches and displays all products. Each product links to its detail page. Supports search and filter._

- **ProductItemDetails**  
  _Shows detailed information of a single product, including images, description, and allows adding items to the cart._

- **Cart**  
  _Lists cart items, allows changing quantity, removing products, and displays a cart summary component._

- **CartItem**  
  _Shows a single product in the cart with image, info, increment/decrement and removal options._

- **CartSummary**  
  _Dynamically updates to show total items and the price whenever the cart changes._

- **Header**  
  _Persistent top navigation bar, includes route links and a badge with the current number of items in the cart._

- **ProtectedRoute**  
  _Prevents unauthenticated access to key routes, redirecting as necessary._

- **NotFound**  
  _Renders a simple 404 page for all unknown routes._

- **CartContext**  
  _Holds cart state globally, with methods for all necessary cart operations throughout the app._

---

## How to Run Locally

1. **Clone this repository:**
git clone https://github.com/hemanthpallapothu/NxtTrendz.git
cd NxtTrendz


2. **Install dependencies:**
npm install


3. **Start the development server:**
npm start


4. Access in your browser:  
[http://localhost:3000/login](http://localhost:3000/login)

Login with:
- Username: **rahul**
- Password: **rahul@2021**

---

## License

This project is for educational and demonstration purposes.

---
