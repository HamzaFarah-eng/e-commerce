E-Commerce Backend API

A scalable E-Commerce Backend API built with ASP.NET Core Web API following Onion Architecture principles.
The project provides core e-commerce functionality including authentication, product management, shopping cart operations, and order processing.

🚀 Features
🔐 User Authentication & Authorization using JWT
👤 User Registration / Login
🛍️ Product Catalog Management
🛒 Shopping Cart System
📦 Order Creation & Management
🧱 Clean Layered Architecture (Onion Architecture)
📄 Swagger API Documentation
🗄️ Entity Framework Core with SQL Server
🏗️ Project Architecture

The solution is divided into three main layers:

1. Core Layer

Contains:

Entities / Models
Interfaces
Business Rules
2. Infrastructure Layer

Contains:

Entity Framework Core
Database Context
Repositories
Identity Configuration
3. API Layer

Contains:

Controllers
Authentication
Middleware
Dependency Injection
🛠️ Technologies Used
ASP.NET Core Web API
Entity Framework Core
SQL Server
ASP.NET Identity
JWT Authentication
Swagger / OpenAPI
C#
🔐 Authentication

This project uses JWT Bearer Token Authentication.

Endpoints:
POST /api/auth/register
POST /api/auth/login

After login, include token in requests:

Authorization: Bearer YOUR_TOKEN
🛍️ Main Modules
Products
Get all products
Get product details
Add / Update / Delete products (Admin)
Cart
Add item to cart
Update quantity
Remove item
View current cart
Orders
Create order from cart
View user orders
Update order status
⚙️ Getting Started
Prerequisites
.NET SDK
SQL Server
Visual Studio / VS Code
Installation
Clone repository:
git clone https://github.com/your-username/e-commerce.git
Navigate to project folder:
cd e-commerce
Update connection string in appsettings.json
Apply migrations:
dotnet ef database update
Run project:
dotnet run
📄 API Documentation

After running the project, open Swagger:

https://localhost:{port}/swagger
