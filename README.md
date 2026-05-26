# Employee-Management-System


A simple **Spring Boot CRUD Application** to manage employee data.
This project helps beginners understand how to build REST APIs using **Java, Spring Boot, Spring Data JPA, and MySQL**.

---

# 🚀 Features

* Add Employee
* Update Employee
* Delete Employee
* Get Employee By ID
* Get All Employees
* REST API Development
* MySQL Database Integration
* Layered Architecture

---

# 🛠️ Technologies Used

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA
* Hibernate
* MySQL
* Maven
* REST API

---

# 📂 Project Structure

```bash
src/main/java
 ├── controller
 │     └── EmployeeController.java
 ├── service
 │     ├── EmployeeService.java
 │     └── EmployeeServiceImpl.java
 ├── repository
 │     └── EmployeeRepository.java
 ├── entity
 │     └── Employee.java
 └── EmployeManagementProjectApplication.java
```

---

# ⚙️ Setup & Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/employee-management-system.git
```

---

## 2️⃣ Open Project

Open the project in:

* IntelliJ IDEA
* Eclipse
* VS Code

---

## 3️⃣ Configure Database

Update your `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## 4️⃣ Run Project

Run the main file:

```bash
EmployeManagementProjectApplication.java
```

Or run using Maven:

```bash
mvn spring-boot:run
```

---

# 📌 API Endpoints

## Add Employee

```http
POST /employees
```

## Get All Employees

```http
GET /employees
```

## Get Employee By ID

```http
GET /employees/{id}
```

## Update Employee

```http
PUT /employees/{id}
```

## Delete Employee

```http
DELETE /employees/{id}
```

---

# 📸 Sample JSON

```json
{
  "name": "Abhishek",
  "department": "IT",
  "salary": 50000
}
```

---

# 🧠 Learning Outcomes

By building this project, I learned:

* Spring Boot Project Structure
* REST API Development
* CRUD Operations
* Dependency Injection
* Database Connectivity
* Layered Architecture
* JPA & Hibernate
* Exception Handling

---

# 🔮 Future Improvements

* Add Frontend using React or Angular
* Add JWT Authentication
* Add Validation
* Add Swagger Documentation
* Deploy on Cloud

---

# 🤝 Contributing

Contributions are welcome.
Feel free to fork this repository and improve the project.

---

# 📧 Contact

If you like this project, connect with me on LinkedIn and GitHub.

---

# ⭐ Support

If you found this project useful, give it a ⭐ on GitHub.
