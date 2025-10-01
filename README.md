# 🛒 DonKampo – Case Study on Distribution SaaS Platform

A case study of a wholesale and distribution SaaS built for multi-client commerce in Colombia, featuring custom pricing, admin panel, PDF invoices, and PWA support.

---

## 🌍 Overview

DonKampo provides an integrated solution for distribution companies and their clients in Colombia.  

The platform supports different customer types (households, restaurants, produce shops, supermarkets), each with personalized access to products and prices.  

---

## ✨ Features

- 👥 Multi-client user roles (households, restaurants, produce shops, supermarkets)  
- 💰 Dynamic pricing & product availability based on client type  
- 🛒 Cart management with adjustable quantities before checkout  
- 📄 Automatic PDF invoice generation and order tracking  
- 📲 PWA installation on mobile & desktop  
- 📊 Admin dashboard with:  
  - User statistics by type  
  - Sales reports (Excel export + bar chart visualization)  
  - Adjustable shipping costs per client type  
  - Advertising management (CRUD for ads)  
  - Product management with Excel import/export for mass updates  

---

## 🛠 Tech Stack

- **Frontend:** React.js, Vite, CSS3  
- **Backend:** Node.js, Express.js  
- **Database:** MySQL  
- **Authentication:** JWT  
- **File Handling:** Multer (images & products)  
- **PDF:** Invoice generation at checkout  
- **Excel:** Reporting & product import/export  
- **PWA:** Mobile/desktop installation mode  
- **Admin Panel:** Full management of users, products, ads, and reports  

---

## 📂 Project Structure

```text
client/
 ├── public/
 ├── src/
 │   ├── assets/
 │   ├── components/
 │   ├── css/
 │   ├── fonts/
 │   ├── utils/
 │   ├── App.jsx
 │   └── main.jsx
 └── index.html

server/
 ├── src/
 │   ├── config/
 │   ├── controllers/
 │   ├── database/
 │   ├── helpers/
 │   ├── middlewares/
 │   ├── migration/
 │   ├── routes/
 │   └── index.js
 └── web/
     └── index.ejs
```

---

## 📸 Showcase

_(Screenshots, GIFs or demo videos can be added here)_

---

## ⚙️ Installation & Setup

⚠️ This project was developed for a private client and is not publicly available.

---

## 📖 Case Study

I joined the project halfway through its development, completing the remaining features and working on both frontend and backend improvements.

The main challenge was ensuring seamless integration between multi-client roles, dynamic product catalogs, PDF invoice generation, and admin reporting tools.

The final product became a fully functional SaaS-like platform, optimized for distribution companies with scalability in mind.

---

## 📈 Future Improvements

- ☁️ Cloud-based deployment for scaling across regions
- 📱 Mobile-first dashboard for administrators
- 🔄 Real-time stock synchronization across multiple warehouses
- 💳 Integration with local payment gateways
- 🌐 Expansion for multi-country support

---

## 📜 License

This project was developed for a private client and is **not open-source**.
