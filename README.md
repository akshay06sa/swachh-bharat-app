# Swachh Bharat Complaint & Monitoring App

A simple entry-level full-stack application for reporting and tracking cleanliness complaints, built with Spring Boot, Angular, and MySQL.

## 📝 Description

This project enables users to register, log in, and manage (create, view, edit, delete) their cleanliness complaints via a web interface. It demonstrates a full-stack workflow:

* **Frontend**: Angular SPA
* **Backend**: Spring Boot REST API
* **Database**: MySQL
* **Authentication**: JWT-based security

## 🚀 Tech Stack

* **Spring Boot** (Java 17)
* **Angular** (v16)
* **MySQL** (v8)
* **Spring Security** + **JWT**
* **Maven & Node.js**

## 📦 Prerequisites

* Java 17
* Maven 3.x
* Node.js 16+ & npm
* MySQL Server

## ⚙️ Setup & Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/akshay06sa/swachh-bharat-app.git
   cd swachh-bharat-app
   ```

2. **Configure Database**

   * Create a MySQL database named `swachh_app`
   * Update credentials in `backend/src/main/resources/application.properties`

3. **Run Backend Service**

   ```bash
   cd backend
   mvn spring-boot:run
   ```

4. **Run Frontend App**

   ```bash
   cd frontend
   npm install
   ng serve --open
   ```

5. **Access the App**
   Open your browser at `http://localhost:4200`

## 📄 API Endpoints (MVP)

* `POST /api/auth/register` - Register new user
* `POST /api/auth/login`    - Authenticate user & receive JWT
* `GET /api/complaints`     - List user complaints
* `POST /api/complaints`    - Create new complaint
* `PUT /api/complaints/{id}` - Update complaint
* `DELETE /api/complaints/{id}` - Delete complaint

## 🛠️ Project Structure

```
swachh-bharat-app/
├── backend/    # Spring Boot API
└── frontend/   # Angular application
```

---

*Start building your entry-level full-stack project today!*
