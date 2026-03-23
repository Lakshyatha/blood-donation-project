# 🩸 Blood Donation Management System

A full-stack web application that helps users find blood donors, register donors, and request blood instantly.

---

## 🚀 Features

* 🧑‍🤝‍🧑 Donor Registration
* 🔍 Search donors by blood group & city
* 🩸 Request blood from donors
* 🤖 AI-powered chatbot for assistance
* 📊 Donor list with filters
* ⚡ Real-time API integration

---

## 🛠️ Tech Stack

### Backend

* Spring Boot
* JPA / Hibernate
* REST APIs

### Frontend

* React.js
* Vite

### Database

* MySQL / Supabase PostgreSQL

### Tools

* Postman
* GitHub
* VS Code / STS

---

## 📂 Project Structure

```
backend/
 ├── controller/
 ├── entity/
 ├── repository/
 ├── service/

frontend/
 ├── components/
 ├── pages/
```

---

## ▶️ How to Run

### Backend

```
cd blooddonation
./mvnw spring-boot:run
```

Runs on: `http://localhost:8082`

---

### Frontend

```
cd frontend
npm install
npm run dev
```

Runs on: `http://localhost:5173`

---

## 📡 API Endpoints

* `POST /donors` → Add donor
* `GET /donors` → Get all donors
* `PUT /donors/{id}` → Update donor
* `DELETE /donors/{id}` → Delete donor

---

## 💡 Future Enhancements

* 📍 Location-based donor search
* 📱 WhatsApp integration
* 🔐 User authentication
* 🔔 Emergency blood alerts

---
