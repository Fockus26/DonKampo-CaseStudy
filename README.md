# 🛒 DonKampo – Case Study on Distribution SaaS

**English**

Case study of a web application for distribution and wholesale commerce in Colombia.
I joined the project halfway through its development, completing the remaining features and making changes on both the frontend and backend.

DonKampo was designed as a multi-client distribution platform, where different types of customers (households, restaurants, produce shops, supermarkets) can register, log in, and access customized products and prices.

The platform also includes a PWA (Progressive Web App) mode for mobile and desktop use, a PDF invoice generator, and a complete admin panel with product, user, and sales management tools.

**Español**

Estudio de caso de una aplicación web para la distribución y el comercio mayorista en Colombia.
Me incorporé al proyecto a mitad de su desarrollo, completando las funcionalidades restantes y realizando cambios tanto en el frontend como en el backend.

DonKampo fue diseñado como una plataforma de distribución multi-cliente, donde diferentes tipos de clientes (hogares, restaurantes, fruver, supermercados) pueden registrarse, iniciar sesión y acceder a productos y precios personalizados.

La plataforma también incluye un modo PWA (Progressive Web App) para usar en dispositivos móviles y computadoras, un generador de facturas en PDF y un completo panel de administración con gestión de productos, usuarios y ventas.

---

## 🌍 Overview

**English**

DonKampo provides an integrated solution for distribution companies and their clients.

The platform includes:

- 👥 Multi-client registration and authentication (households, restaurants, produce shops, supermarkets).

- 💰 Dynamic product catalog with role-based prices and product availability.

- 🛒 Shopping cart with quantity management before checkout.

- 📄 PDF invoice generation with order tracking in the user panel.

- 📲 Progressive Web App support for mobile/desktop install.

- 📊 Admin dashboard with:

    - User statistics by type.

    - Sales reports (Excel export + bar chart visualization).

    - Adjustable shipping costs per client type.

    - Advertising management (CRUD for ads).

    - Product management with mass update via Excel import/export.

**Español**

DonKampo ofrece una solución integrada para empresas distribuidoras y sus clientes.

La plataforma incluye:

- 👥 Registro y autenticación multi-cliente (hogares, restaurantes, fruver, supermercados).

- 💰 Catálogo dinámico de productos con precios y disponibilidad según el tipo de cliente.

- 🛒 Carrito de compras con gestión de cantidades antes del checkout.

- 📄 Generación de facturas en PDF con seguimiento de órdenes en el panel de usuario.

- 📲 Soporte para Progressive Web App en móviles y computadoras.

- 📊 Panel de administración con:

    - Estadísticas de usuarios por tipo.

    - Reportes de ventas (exportación a Excel + visualización en gráfico de barras).

    - Configuración del costo de envíos por tipo de cliente.

    - Gestión de publicidad (crear, editar, eliminar anuncios).

    - Gestión de productos con actualización masiva vía importación/exportación de Excel.

---

## 🛠️ Tech Stack

Frontend: React, JavaScript, SASS/CSS

Backend: Node.js, Express

Database: MySQL

Other: PWA, PDF generation, Excel export/import

---

## 📂 Project Structure
```text
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

## 📜 License / Licencia

**English**

This project was developed for a client and is not open-source.

**Español**

Este proyecto fue desarrollado para un cliente y no es de código abierto.
