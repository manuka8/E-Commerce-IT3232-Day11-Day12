

# 🛒 E-Commerce IT3232 - Day 11 & Day 12 Project

This is a Spring Boot-based backend project developed as part of the **IT3232 coursework** at the **University of Jaffna**, focused on building an e-commerce system. The backend supports core e-commerce functionalities such as product management, customer interactions, and order processing.

---

## 🚀 Getting Started

### ✅ Prerequisites

* Java 11 or later
* Maven 3.6+
* An IDE (e.g., IntelliJ IDEA, Eclipse)

---

### ▶️ Running the Application

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/E-Commerce-IT3232-Day11-Day12-main.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd E-Commerce-IT3232-Day11-Day12-main/day11
   ```

3. **Build the project:**

   ```bash
   mvn clean install
   ```

4. **Run the application:**

   ```bash
   mvn spring-boot:run
   ```

The application will start at: [http://localhost:8080](http://localhost:8080)

---

## 📦 Technologies Used

* Java 11
* Spring Boot
* Spring Data JPA
* H2 / MySQL (for database)
* Maven

---

## 📂 Project Structure

* **`controller/`** – Handles REST API endpoints
* **`model/`** – Contains the data entities
* **`repo/`** – Interfaces for database operations (Repositories)
* **`exceptionHandler/`** – Custom exception handling

---

## ✅ Features

* Full CRUD operations for:

  * Products
  * Customers
  * Orders
* Custom exception handling
* RESTful API structure
* Easily switchable between H2 and MySQL databases

---

## ⚙️ Notes

* By default, the application is configured to use an **in-memory H2 database**.
* To use **MySQL** or another database:

  * Update `application.properties` in the `resources/` folder with your desired database configurations.

---



