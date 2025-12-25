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


---

## Deployment

The project is deployed using Vercel and connected to MongoDB Atlas , Cloudinary using environment variables.
<img width="1919" height="1016" alt="Screenshot 2025-12-25 203542" src="https://github.com/user-attachments/assets/4a17aeb5-ac0b-4faf-98ac-37536a58c813" />
login page

<img width="1919" height="1015" alt="Screenshot 2025-12-25 203619" src="https://github.com/user-attachments/assets/9ba30649-1fd5-41e3-bea3-d16fa6dfd48d" />
<img width="1894" height="925" alt="Screenshot 2025-12-25 203643" src="https://github.com/user-attachments/assets/f7c8d103-90d9-4fd5-bce0-5197d8427965" />
Dashboard page




---

