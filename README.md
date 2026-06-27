# 🚀 Full Stack Development — Project 2: Backend API Development

> **DecodeLabs Industrial Training Kit · Batch 2026**

![Project](https://img.shields.io/badge/Project-2%20Backend%20API-2563EB?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-10B981?style=for-the-badge)
![Batch](https://img.shields.io/badge/Batch-2026-06B6D4?style=for-the-badge)
![DecodeLabs](https://img.shields.io/badge/Powered%20by-DecodeLabs-0B1E3D?style=for-the-badge)

---

## 👩‍💻 About Me

**Esha Saleem**  
Full Stack Development Intern @ DecodeLabs  
- 🔗 LinkedIn: [esha-saleem](https://www.linkedin.com/in/esha-saleem-8a5522360)  
- 💻 GitHub: [eshasaleem09](https://github.com/eshasaleem09)  
- 📧 Email: eshas1734@gmail.com  

---

## 📌 Project Overview

Project 2 is the **integration phase** of Full Stack Development —
focused entirely on **Backend API Development**.

> *"Project 1 was the skin. Project 2 is the life."*  
> — DecodeLabs

This project is not about visual flair. It is about the
**application's brain** — building robust endpoints and managing
the flow of data between the frontend and the server through
pure API logic.

---

## 🌐 Live Demo

👉 [View Live Website](https://eshasaleem09.github.io/project-2-backend-api/)

---

## 🎯 Goal

Develop a simple but production-ready backend API to handle
application logic with absolute reliability.

---

## ✅ Key Requirements

| Requirement | Status |
|---|---|
| Create GET endpoints | ✅ Done |
| Create POST endpoints | ✅ Done |
| Handle user input & responses | ✅ Done |
| Validate basic data | ✅ Done |
| Return correct HTTP status codes | ✅ Done |
| Document all endpoints | ✅ Done |

---

## 🧠 Core Concepts Covered

### 1. The IPO Model
Input → Process → Output.  
Every API request is a cycle — receive data, compute, respond.  
Control the inputs and you predict the outputs.

### 2. The Gatekeeper Rule
> *"Never Trust the Client."*

Two layers of validation on every request:
- **Syntactic Validation** — Is the format correct?
- **Semantic Validation** — Is the logic valid?

### 3. RESTful Naming
> *"Resources are Nouns. Methods are Verbs."*

| ❌ Wrong | ✅ Correct |
|---|---|
| GET /getUsers | GET /users |
| POST /createUser | POST /users |
| GET /users.xml | GET /users/{id} |

### 4. HTTP Methods

| Method | Purpose | Safe | Idempotent |
|---|---|---|---|
| GET | Retrieve resource | ✅ | ✅ |
| POST | Create resource | ❌ | ❌ |
| PUT | Update/Replace resource | ❌ | ✅ |
| DELETE | Remove resource | ❌ | ✅ |

### 5. HTTP Status Codes

| Code | Name | When to Use |
|---|---|---|
| 200 | OK | Successful GET / PUT |
| 201 | Created | Successful POST |
| 204 | No Content | Successful DELETE |
| 400 | Bad Request | Validation failed |
| 401 | Unauthorized | Not authenticated |
| 403 | Forbidden | No permission |
| 404 | Not Found | Resource missing |
| 500 | Internal Server Error | Unexpected failure |

### 6. JSON — The Neurotransmitter
Lightweight. Machine-parsable. Human-readable.  
The universal language between client and server.

```json
{
  "user": {
    "id": 101,
    "profile": {
      "role": "admin"
    }
  }
}
```

### 7. Gateway Architecture
Client → API Gateway → Auth Service

→ Users Service  → Database

→ Posts Service
Decoupling logic. Centralizing control.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Node.js | Runtime environment |
| Express.js | API framework |
| JavaScript | Programming language |
| JSON | Data format |
| Postman | API testing |
| Git & GitHub | Version control |

---

## 📁 Project Structure
project-2-backend-api/

│

├── index.html          # Portfolio website

└── README.md           # Project documentation

---

## 🔐 Security Principles Applied

- ✅ Input validation on every endpoint
- ✅ Proper error messages (no internal details exposed)
- ✅ Authentication (AuthN) — Who are you?
- ✅ Authorization (AuthZ) — What can you do?
- ✅ Stateless requests
- ✅ Circuit breakers for failure isolation

---

## 📖 Key Lesson

> *"If it isn't documented, it doesn't exist."*

An API without documentation is unusable.  
Your users are other developers — treat them with respect.

---

## 🏆 Qualification

> ✅ **Project 2 Badge Earned**  
> Completing this project unlocks further projects  
> and is the vital bridge to professional development.

---

## 📞 Contact

Made with 💙 by **Esha Saleem**

| Platform | Link |
|---|---|
| LinkedIn | [esha-saleem-8a5522360](https://www.linkedin.com/in/esha-saleem-8a5522360) |
| GitHub | [eshasaleem09](https://github.com/eshasaleem09) |
| Email | eshas1734@gmail.com |

---

*© 2026 Esha Saleem · DecodeLabs Industrial Training · Batch 2026*
