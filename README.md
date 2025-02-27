# 🛒 E-Commerce Backend - Spring Boot Microservices
# 🚀 Overview
This project is a Spring Boot-based E-Commerce Backend designed with a Microservices Architecture. It includes secure user authentication, product and category management, shopping cart functionality, and image handling. The backend is secured using Spring Security & JWT, ensuring safe transactions and access control.

# 📌 Key Features
✅ User Authentication & Authorization – Secure login & role-based access using Spring Security & JWT 🔐
✅ Product Management – Add, update, and fetch products from the catalog 🛍️
✅ Category Management – Organize products into categories 📂
✅ Shopping Cart System – Add and manage products in the cart 🛒
✅ Image Handling – Store and retrieve product images 🖼️
✅ RESTful APIs – Well-structured endpoints for seamless frontend integration 🌐

# 🏗️ Tech Stack Used
* Spring Boot – Backend framework
* Spring Security & JWT – Authentication & authorization
* Spring Data JPA – Database interaction
* PostgreSQL/MySQL – Database
* Lombok – Reducing boilerplate code
* Docker – Containerization for deployment
# 🛠️ Microservices in the Project
The system consists of five microservices, each handling a specific e-commerce functionality:

1️⃣ Product Service (productMS)
* Manages product details (name, price, stock, etc.)
* Provides endpoints for product listing and search
2️⃣ Image Service (imageMS)
* Handles product image uploads and retrieval
* Stores images securely and maps them to products
3️⃣ Category Service (categoryMS)
* Organizes products into different categories
* Enables category-based product filtering
4️⃣ Cart Service (addCartMS)
* Allows users to add/remove products from the cart
* Handles cart calculations (total price, quantity updates)
5️⃣ User Service (userMS)
* Handles user authentication, roles, and profile management
* Uses JWT & Spring Security for secure access
# 📲 Installation & Setup
* Prerequisites
📌 Java 17+
📌 Maven
📌 MySQL (or Docker for database)

![image alt](https://github.com/patelaviral/spring-boot-eCommerce/blob/422924d72e1af7fb1efa891162ceaf4d61854c12/Screenshot%202024-12-10%20225632.png)

🎯 Future Enhancements
✅ Implement Order & Payment Microservices 💳
✅ Integrate Cloud Storage for images ☁️
✅ Add Kafka for event-driven communication 📢
✅ Deploy on AWS/GCP 🚀
