# Product Management Dashboard

This project is a **Product Management Dashboard** which allows an admin to manage products and monitor inventory using tables and charts.

---

## Project Overview

The dashboard provides a simple interface where an admin can:

- Add new products,edit existing products and delete products
- View stock availability
- Analyze inventory using charts

The project also includes a **dummy admin login system** to restrict dashboard access.

---

## Features

- Product CRUD operations (Create, Read, Update, Delete)
- Input validation for product details
- Stock status indicator (Low Stock / In Stock)
- Product image upload
- Stock Distribution chart
- Total Inventory Value per Product chart
- Dummy admin authentication
- Protected dashboard route

---

## Admin Login (Dummy Credentials)

Use the following credentials to access the dashboard:

Username: admin  
Password: admin123  

This authentication system is created only for demonstration purposes.

---

## How Authentication Works

- The admin logs in using dummy credentials.
- On successful login, a flag is stored in the browser.
- The dashboard checks this flag before rendering.
- If the admin is not logged in, the user is redirected to the login page.
- Logging out clears the login state.

---

## Charts and Analytics

The dashboard includes two charts:

1. Stock per Product Chart  
   Shows the stock count for each product.

2. Total Inventory Value per product Chart  
   Displays the total inventory value calculated as price multiplied by stock.

The charts update automatically when product data changes.

---

## Tech Stack Used

- Next.js (Pages Router)
- React
- MongoDB
- SWR
- Recharts
- JavaScript
- CSS
- Cloudinary
- Zod

---

## How to Run the Project Locally

1. Install dependencies:
   npm install

2. Start the development server:
   npm run dev

3. Open the application in browser:
   http://localhost:3000

---

## Deployment

The project is deployed using Vercel and connected to MongoDB Atlas using environment variables.

---

