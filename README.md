# Fashion Store App

A full-stack web application for managing an online fashion store, consisting of an Angular frontend and a Spring Boot backend that provides RESTful APIs for user authentication, product management, shopping cart, and order processing.

---

## 🌐 Tech Stack

### Frontend

* **Angular** (TypeScript)
* HTML, CSS
* Angular Router, Reactive Forms
* runs by default on `http://localhost:4200`

### Backend

* **Java Spring Boot**
* Spring Data JPA (for persistence)
* MySQL (configurable)
* runs by default on `http://localhost:8080`

---

## 📊 Features

* User Registration and Login
* Product Catalog with Filtering
* Add to Cart / Remove from Cart
* Place Orders
* View Order History

---

## 🔄 API Overview (Backend)

* `POST /api/auth/register` – Register new users
* `POST /api/auth/login` – Authenticate users
* `GET /api/products` – Get all products
* `POST /api/cart` – Add item to cart
* `GET /api/cart` – Get user cart
* `POST /api/orders` – Place order

> More endpoints available in the source code under `UserController.java`

---
