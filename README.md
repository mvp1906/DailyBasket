# 🛒 DailyBasket – Grocery E-Commerce Web Application

**DailyBasket** is a .NET Core MVC web application designed to provide a modern and user-friendly online grocery shopping experience. It supports product browsing, cart management, secure checkout, and order tracking, and features a role-based admin panel.

---

## 📁 Project Structure Overview

```
DailyBasket/
├── Controllers/             # MVC Controllers (Cart, Checkout, Products, etc.)
├── Models/                  # Data models (Product, CartItem, Order, User, etc.)
├── Views/                   # Razor views (.cshtml for pages)
├── wwwroot/                 # Static assets (CSS, JS, images)
├── Migrations/              # Entity Framework Core migrations
├── appsettings.json         # Configuration settings
├── Program.cs               # Entry point
├── DailyBasket.csproj       # Project file
├── DailyBasket.sln          # Solution file
```

---

## ✅ Features

- 🛍️ Browse grocery items by category
- 🛒 Add to cart and modify item quantities
- 💳 Checkout with input validation and card masking
- 🔐 Authentication and role-based access
- 📦 Order placement and viewing order history
- 📊 Admin dashboard to manage orders
- 📱 Fully responsive and mobile-friendly design

---

## 🛠️ Technologies Used

- ASP.NET Core MVC
- Entity Framework Core (Code First)
- C#, Razor Pages
- SQL Server / LocalDB
- Bootstrap, CSS, JavaScript
- Identity for Authentication

---

## 🚀 Getting Started

### Prerequisites

- Visual Studio 2022 or later
- .NET 6 SDK or higher
- SQL Server (LocalDB or full instance)

### Steps to Run

1. Open the `.sln` file in Visual Studio
2. Update `appsettings.json` for your DB connection
3. Run migrations:
   ```bash
   dotnet ef database update
   ```
4. Press F5 or use "Start" to launch the app

---

## 📌 Future Enhancements

- Payment gateway integration
- Inventory alerts for admin
- Email notifications for order confirmations
- Wishlist and product ratings

---

## 👤 Author

**Vijay Prakash Mudaliar**  
📧 [mudaliarvijay196@gmail.com](mailto:mudaliarvijay196@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/vijay-mudaliar)

---

> 🧠 *Built as a full-stack grocery eCommerce platform using the ASP.NET MVC framework for academic and portfolio demonstration.*
