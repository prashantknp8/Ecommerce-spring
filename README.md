# E-Commerce Spring Boot Application

A fully-featured eCommerce web application built with **Spring Boot**, **Thymeleaf**, and **Bootstrap**.  
This project includes essential eCommerce functionalities such as product and category management, order processing, user authentication with roles, and more.

---

## Features

- **Product Management**  
  - Create, Read, Update, Delete (CRUD) operations for products  
  - Search products by name or category  
  - Pagination support for product listings  

- **Category Management**  
  - CRUD operations for product categories  

- **Order Management**  
  - View and update orders  
  - Order status updates with email notifications  

- **User Management**  
  - User registration and profile management  
  - Multiple admin roles with role-based authentication and authorization  
  - Account lock and unlock after configurable number of failed login attempts  
  - User account block/unblock by admin  

- **Security**  
  - Role-based authentication (USER, ADMIN)  
  - Account lockout on multiple failed login attempts  
  - Email-based account verification and password reset  
  - Secure password storage with encryption  

- **Shopping Cart**  
  - Add to cart feature  
  - Update and remove items from the cart  

- **Email Integration**  
  - Email notifications for account verification, order updates, and messaging  

- **UI/UX**  
  - Responsive design with Bootstrap  
  - Dynamic pages rendered using Thymeleaf templates  

---

## Technologies Used

- **Backend:** Spring Boot, Spring Security, Spring Data JPA, Hibernate  
- **Frontend:** Thymeleaf, Bootstrap 5  
- **Database:** MySQL / H2 (or your preferred relational database)  
- **Build Tool:** Maven  
- **Email:** Spring Boot Starter Mail  
- **Authentication:** Role-based, JWT or session-based (depending on implementation)  

---

## Getting Started

### Prerequisites

- Java 17 or higher  
- Maven 3.x  
- MySQL Server (or other compatible database)  
- An email SMTP server for sending verification and notification emails  

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/ecommerce-springboot.git
   cd ecommerce-springboot




