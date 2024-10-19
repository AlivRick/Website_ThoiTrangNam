# **E-commerce Application**

## Description

This **E-commerce Application** is a comprehensive web platform that allows users to shop for fashion products online. Built with **.NET Core MVC** for the backend and **Razor Pages** for the frontend, the application enables users to browse products, add items to the cart, proceed with checkout, and manage orders with ease.

- **Motivation:** The project was motivated by the need to create a seamless online shopping experience that combines a modern user interface with robust backend functionality.
- **Why was this built?** This project was developed to provide an intuitive and secure online shopping platform where customers can easily find and purchase fashion products. It also aims to simplify order management for administrators through a user-friendly interface.
- **Problem it solves:** The system tackles issues such as complicated checkout processes, inefficient payment integrations, and a lack of real-time inventory management.
- **What did I learn?** Through this project, I gained valuable experience in integrating **OAuth2** for Google and Facebook logins, working with payment gateways like **VNPay** and **PayPal**, managing RESTful APIs, and handling authentication and authorization with **JWT** in **.NET Core**.

---

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Features](#features)

---

## Installation

### Backend (.NET Core MVC)

#### Prerequisites
- .NET Core SDK (v5.0 or higher)
- Visual Studio or VS Code

#### Steps
1. Clone the repository from GitHub and open the solution in **Visual Studio**.
2. Ensure all required **NuGet packages** are restored.
3. Build and run the backend to start the server.

### Frontend (Razor Pages)

#### Prerequisites
- .NET Core SDK (v5.0 or higher)

#### Steps
1. Open the frontend project in Visual Studio.
2. Build and run the frontend project to launch the website.

---

## Usage

Once both backend and frontend are running, navigate to `http://localhost:5000` in your browser. Below are some screenshots showcasing key features:

- **Homepage:**

  ![Homepage](https://github.com/user-attachments/assets/e73a4569-3044-437c-9658-3d5f821e9664)


- **Product Page:**

  ![Product Page1](https://github.com/user-attachments/assets/e0a9551f-845c-47a5-8a0e-89a69ae65041)
  ![Product Page2](https://github.com/user-attachments/assets/a3f2c914-c209-407c-b042-f537c0c2d37d)



- **Cart Page:**

  ![Cart Page](https://github.com/user-attachments/assets/3b7c23a7-dd8e-440f-acdf-73096fe2c432)


- **Checkout Page:**

  ![Checkout Page](https://github.com/user-attachments/assets/894c9892-e3c9-426a-b4b4-c3a4ca3bed00)


- **Payment Integration (VNPay/PayPal):**

  ![Payment](https://github.com/user-attachments/assets/cb939284-19ff-47a9-9a71-e188babfdd47)


- **Email:**

  ![Email]
  (https://github.com/user-attachments/assets/968ec09b-f159-4b74-bbaf-0f18a1a6ed20)
  ![Change your password after confirming your email](https://github.com/user-attachments/assets/380138c2-e0d5-47fd-975c-e2b64d03ed5c)



- **Admin:**

  ![Admin Dashboard]!(https://github.com/user-attachments/assets/8b7c9b2f-d773-4320-8a04-f1da3f517d8a)

- **Order Management:**

  ![Order Management](https://github.com/user-attachments/assets/2f7d5982-2b50-48ea-b5f7-8ef00b7a66d6)


--- 

## Credits

- **[Hoàng Châu Phúc Thuận]** - Fullstack Developer
- **[Trần Hoài Nam]** - Fullstack Developer

---

## Features
- **OAuth2** Login using Google/Facebook
- **JWT Authentication** for securing API requests
- **Product management** with CRUD functionality
- **Shopping cart** with real-time updates
- **Payment integration** via **VNPay** and **PayPal**
- **Order confirmation email** sent through **SMTP**
- **Admin panel** for product and order management
- **CKEditor** for product descriptions with image/video support
- **Sales reporting** with charts and Excel export
- **Invoice generation** in PDF format
- **Responsive design** for optimal viewing on mobile and desktop
