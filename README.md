# 🚀 CeranTech | Premium E-Commerce Platform

![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Material UI](https://img.shields.io/badge/Material--UI-5.0-0081CB?style=for-the-badge&logo=mui&logoColor=white)

**CeranTech** is a full-stack e-commerce web application designed to provide a premium shopping experience for high-end technology products. This project demonstrates a robust integration between a **Spring Boot** RESTful backend and a modern **React** frontend, featuring strict security validations and a responsive UI.

---

## 🌟 Key Features

* **🛒 Dynamic Shopping Cart:** Add/remove items with real-time price calculation.
* **🔍 Instant Search & Filtering:** Filter products by category (Phones, Laptops, Audio) and search by name simultaneously without page reload.
* **🔒 Secure Authentication (Strict Mode):**
    * **Input Validation:** Prevents junk data entry (e.g., "..." or "111") using Regex.
    * **Rules:** Usernames must be alphanumeric (4+ chars), and passwords must be secure.
* **💾 Persistent User Session:** Uses LocalStorage to keep users logged in even after refreshing the page.
* **📱 Responsive Design:** Built with Material UI (MUI) for a seamless experience on desktop and mobile.
* **⚙️ Smart Pricing Logic:** Automatic price adjustment based on product variations (e.g., selecting 1TB storage updates the price instantly).

---

## 🛠️ Tech Stack

### Backend
* **Language:** Java 17
* **Framework:** Spring Boot 3+
* **Database:** PostgreSQL
* **ORM:** Hibernate / Spring Data JPA
* **Build Tool:** Maven

### Frontend
* **Library:** React.js
* **UI Framework:** Material UI (MUI)
* **HTTP Client:** Axios
* **State Management:** React Hooks (useState, useEffect)

---

