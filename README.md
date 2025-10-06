# 🎞️ MyImages – Online Photo Printing System

MyImages is a full-featured **Online Photo Printing System** built with **ASP.NET MVC (C#)**.  
It allows users to upload JPEG photos, select print sizes, choose payment methods, and manage their orders online — while the admin can manage pricing, orders, and user activities.

---

## 🚀 Features

### 🧑‍💻 User Side
- User Registration and Login with session management  
- Upload JPEG photos (multiple uploads supported)  
- Select print sizes and quantities  
- Automatic price calculation from the database  
- Choose payment method:
  - 💳 Credit Card (encrypted)
  - 🏦 Pay at Branch  
- Enter shipping address  
- View order history and status  
- Edit profile, change password, or delete account  

### 🛠️ Admin Side
- Secure admin login  
- Manage users, orders, and pricing  
- Update print size rates  
- View, approve, or reject orders  
- Manage completed and pending orders  

---

## 🧩 Technologies Used

| Category | Tools / Frameworks |
|-----------|--------------------|
| Backend  | ASP.NET MVC (C#), Entity Framework |
| Frontend | HTML5, CSS3, Bootstrap, jQuery |
| Database | SQL Server |
| Security | Credit Card Encryption, Session Management |
| IDE      | Visual Studio 2022 |

---

## 🗂️ Project Structure

MyImages/
│
├── .vs/ # Visual Studio config and cache files
├── e-project/ # Main ASP.NET MVC web application folder
│ ├── Controllers/ # Contains AdminsController, UsersController, PhotoOrdersController, etc.
│ ├── Models/ # Contains User, Order, PhotoOrderItem, Admin models
│ ├── Views/ # Razor views (.cshtml files)
│ ├── Content/ # CSS, Bootstrap files, and static resources
│ ├── Scripts/ # jQuery and custom JS scripts
│ └── web.config # App configuration file
│
└── e-project.sln # Visual Studio Solution file

