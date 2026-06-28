# 🌍 TOURIS - Travel Booking Website

A full-stack **Travel Booking Website** built using **Java, Spring Boot, MySQL, HTML, CSS, and JavaScript**. The application allows users to explore travel destinations, browse travel packages, register/login securely, and book trips through a responsive and user-friendly interface.

---

## ✨ Features

- 👤 User Registration & Login
- 🔐 Secure Authentication using Spring Security
- 🌍 Browse Travel Destinations
- 🎒 Explore Travel Packages
- 📅 Book Travel Packages
- 🔍 Search Destinations
- 📩 Contact/Inquiry Form
- 📱 Responsive User Interface
- ⚡ RESTful APIs
- 🗄️ MySQL Database Integration
- ✅ Input Validation & Exception Handling

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Spring Security
- Maven

### Frontend
- HTML5
- CSS3
- JavaScript

### Database
- MySQL

### Tools
- Git
- GitHub
- IntelliJ IDEA
- VS Code
- Postman

---

## 📂 Project Structure

```
travel
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.travel
│   │   │       ├── config
│   │   │       ├── controller
│   │   │       ├── dto
│   │   │       ├── exception
│   │   │       ├── model
│   │   │       ├── repository
│   │   │       ├── service
│   │   │       └── TravelApplication.java
│   │   │
│   │   ├── resources
│   │   │   ├── static
│   │   │   ├── templates
│   │   │   └── application.properties
│
└── pom.xml
```

---

## 📷 Project Screenshots

### 🏠 Home Page

![Home Page](screenshots/home.png)

---

### 🖼️ Photo Gallery

![Photo Gallery](screenshots/photos.png)

---

### 🎒 Travel Packages

![Travel Packages](screenshots/packages.png)

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/SheetalCarpenter23/TOURIS-Travel-Website.git
```

### 2️⃣ Navigate to Project

```bash
cd TOURIS-Travel-Website/travel
```

### 3️⃣ Configure MySQL

Open:

```
src/main/resources/application.properties
```

Update your database configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/travel_db
spring.datasource.username=root
spring.datasource.password=your_password
```

### 4️⃣ Run the Project

```bash
mvn spring-boot:run
```

Open in browser:

```
http://localhost:8080
```

---

## 📌 Modules

- Authentication Module
- Destination Management
- Booking Management
- Travel Package Management
- Contact Module
- Security Configuration
- Global Exception Handling

---

## 📚 Key Concepts Used

- Object-Oriented Programming (OOP)
- MVC Architecture
- Layered Architecture
- REST API Development
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL
- Exception Handling
- DTO Pattern

---

## 👩‍💻 Author

**Sheetal Carpenter**

- GitHub: https://github.com/SheetalCarpenter23

---

## ⭐ If you like this project, please give it a Star on GitHub.
