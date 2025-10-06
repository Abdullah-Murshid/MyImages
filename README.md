# 🖼️ MyImages  
### Online Photo Printing System (ASP.NET MVC)

MyImages is a web-based platform that allows users to upload, customize, and order printed photos online.  
It’s built using **ASP.NET MVC**, **Entity Framework**, and **SQL Server** — featuring both **user** and **admin** panels.

---

## 🚀 Features

### 👤 User Features
- Register, Login, and Manage Profile  
- Upload JPEG photos  
- Select print size and quantity  
- Automatic price calculation  
- Secure payment via **credit card encryption** or **branch payment**  
- Shipping address management  
- View order history and status  

### 🛠️ Admin Features
- Admin registration and login  
- Manage photo sizes and prices  
- View and process customer orders  
- Update order statuses  
- Manage users  

---

## 🧱 Tech Stack

| Layer | Technology |
|--------|-------------|
| Frontend | HTML5, CSS3, Bootstrap, JavaScript, jQuery |
| Backend | ASP.NET MVC (C#), Entity Framework |
| Database | SQL Server |
| Encryption | AES for credit card data |
| Authentication | Session-based login for users and admins |

---

## ⚙️ Project Structure

Controllers/
│ AdminsController.cs
│ UsersController.cs
│ PhotoOrdersController.cs
│ HomeController.cs
Models/
│ User.cs
│ Admin.cs
│ Order.cs
│ PhotoOrderItem.cs
Views/
│ Admins/
│ Users/
│ PhotoOrders/
│ Home/

---

## 💾 Setup Instructions

1. Clone the repository  
   ```bash
   git clone https://github.com/Abdullah-Murshid/MyImages.git

