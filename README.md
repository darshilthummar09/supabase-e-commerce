# 🛍️ Spring – Full Stack E-commerce Marketplace

Spring is a fully functional, **multi-seller e-commerce marketplace** built with modern technologies. It allows multiple sellers to list their products across various categories, while customers can browse, add to wishlist, place orders, and track them in real-time.  

The platform features **dynamic stock management**, **real-time order tracking**, and **data-rich dashboards** for sellers and customers — making it a scalable solution suitable for real-world scenarios.

---

## 🖼️ Screenshots

Here are a few screenshots of the platform:

![Spring Screenshot 1](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgO933AHnIXwyerGFMPaXP1fNYCAr6AF46z8h66qG_pRrK3QLrBrPaaIdcOlBU2Lcwq-XkyL37uAlCESuOGPIKlQ0bVEnHU7qSJdVek5QyG_n6i52oz0xceFguim3GClRQHA7EfbDEDvdcHLDMlUDyu-6_BFMvSVU6dPlXtgzrFXYejH3xKThDKN0kIrlQ/s1920/Spring.__6_.png)
![Spring Screenshot 2](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi050T0XqfQvhbF6ZKW0zUI9EuPURNaKdgu035xcKVSHbq-CEz2wbjeXvkWO3En-lW7preOu08FiKh-1QYArNODyVr-tDp4t2FC-PvHwKlMT2TY1E52PueWZ3mIAFDRIg00VYdrY1JZtoam88L-Tk8QadtoKGH7P1-ZyMC9I8OORNluKNJA5a4uYxR_9Go/s1920/Capture.PNG)
![Spring Screenshot 3](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgYPl9WHKOmmCpyphxPPwhGBXZ6B4H_8PzZfXGsP5m1Wbaejjnaqh69pXI9W_QtKz2cD0ubWYdkBTY7FLhpfk-mzbXQ1JKEf3ZM_QxkZ2N4_JuB8ONVCsjAcxJg7J8JDzCnspEum_eHitjiWVClK04abQauJvlOdDcO4k4oOmtBEaWme44IzdTWcqZ69hI/s1920/Capture1.PNG)
![Spring Screenshot 4](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjoSPD60h0niKpKLq4K58DnmToyIMSmlXVnPTHM_0vZtXG664QDpsSM7E6klYv6El1bQhFljyRaT7AnrIjgwA1PdQjwkPGw4Wph1C7gbzf9J5KpFH4D7y9WLBX2pa9C1imQSWj-Wuddeihgk0Pc-ATKaNtY352A7fQ6uVDGIz7MioExXqplAzgyFu2BNIE/s1918/Capture2.PNG)

---

## 📚 Table of Contents

- [✨ Key Features](#-key-features)
- [🧰 Tech Stack](#-tech-stack)
- [🧠 Platform Functionality](#-platform-functionality)
  - [👨‍💼 Seller Features](#-seller-features)
  - [🛒 Customer Features](#-customer-features)
  - [📦 Dynamic Product Stock Management](#-dynamic-product-stock-management)
  - [🚚 Order Management](#-order-management)
- [💻 Frontend Overview](#-frontend-overview)
- [🧭 Backend Overview](#-backend-overview)
- [📝 Data Models](#-data-models)
- [⚙️ Environment Variables](#%EF%B8%8F-environment-variables)
- [📜 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## ✨ Key Features

- 🧍 **Multi-Seller Marketplace** – Multiple sellers can list products, manage stock, and handle orders individually.  
- ⚡ **Dynamic Stock Management** – Automatic stock updates on orders and cancellations.  
- 🧩 **Customizable Attributes** – Sellers can add attributes like size, color, etc.  
- ❤️ **Wishlist & Cart** – Customers can wishlist products or add them to cart with live stock checks.  
- 📡 **Real-Time Order Tracking** – Sellers update statuses; customers track live.  
- 📊 **Seller Dashboard** – Chart.js powered insights on orders, sales, and performance.  
- 🔍 **Search, Filter & Pagination** – Better performance and user experience for browsing products.

---

## 🧰 Tech Stack

### 🖥 Frontend
- **React.js** – UI library for building interactive experiences.  
- **Tailwind CSS** – Utility-first CSS framework for rapid styling.  
- **ShadCN UI** – Modern component library for beautiful interfaces.

### 🧠 Backend
- **Supabase** – Open-source backend-as-a-service with PostgreSQL & APIs.  
- **Supabase Storage** – For product and media storage.

### 🔐 Authentication
- **Clerk** – Authentication & session management with social logins.

### 📈 Data Visualization
- **Chart.js** – Real-time charts for dashboards and insights.

---

## 🧠 Platform Functionality

### 👨‍💼 Seller Features
- Add, edit, and manage products with **dynamic attributes** (e.g., size, color).  
- **Real-time stock updates** on orders and cancellations.  
- **Order management panel** to track, ship, deliver, or cancel orders.  
- **Dashboard** with statistics and insights using Chart.js.

### 🛒 Customer Features
- Browse products with **category filters** and attribute selection.  
- Add to **wishlist** or **cart**, with real-time stock validation.  
- Place orders with a smooth **checkout flow**.  
- **Track orders** in real-time (Pending → Shipped → Delivered).  
- Cancel orders before they’re shipped.

### 📦 Dynamic Product Stock Management
- 🧮 **Stock Deduction** – On order placement.  
- ⛔ **Out-of-Stock Handling** – Prevents adding unavailable products.  
- 🔁 **Stock Restoration** – On cancellations.

### 🚚 Order Management
- Multi-stage lifecycle: Pending → Shipped → Delivered → Canceled.  
- Sellers and customers can both interact with the order status appropriately.

---

## 💻 Frontend Overview

- Built with **React**, styled with **Tailwind**, and structured using **ShadCN UI** components.  
- **Responsive** for mobile, tablet, and desktop.  
- Clean separation between **Seller Dashboard** and **Customer Interface**.  
- Dynamic product pages with stock-aware cart and wishlist management.

---

## 🧭 Backend Overview

- Powered by **Supabase**, leveraging:
  - Realtime PostgreSQL for **live updates**.
  - Secure row-level policies for data access.
  - Storage for product images.
- Authentication handled by **Clerk** for both sellers and customers.

---

## 📝 Data Models

- **Users**: Customers & Sellers (role-based).  
- **Products**: Name, description, price, stock, attributes, category.  
- **Orders**: Status, product details, customer, timestamps.  
- **Categories**: Product classification.  
- **Wishlists**: Saved products per user.

---

## ⚙️ Environment Variables

To run this project locally, create a `.env` file in the root and configure the following:

```env
VITE_SUPABASE_URL="https://your-supabase-url"
VITE_SUPABASE_ANON_KEY="your-supabase-anon-key"
VITE_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
