# TASKFLOW – Task Management Backend REST API

## 📌 Project Overview

**TASKFLOW** is a backend REST API built using **Python and Flask** that allows users to securely manage tasks.
It supports user registration, authentication, and full task CRUD operations while following **industry-standard SDLC practices**.

This project is intentionally designed as a **backend-only system** to focus on real software engineering responsibilities rather than UI.

---

## 🎯 Why This Project?

This project was built to simulate **real-world backend development** as done in companies such as service firms, banks, and product companies.

It focuses on:

* Backend architecture
* Clean project structure
* Business logic separation
* Security basics
* REST API standards
* SDLC-based development

---

## ❓ Why This Project WITHOUT Git (Initially)?

This project was **intentionally started without Git** to reflect how beginners should first learn **core backend engineering concepts** before adding tooling.

### Reasoning:

1. **Focus on fundamentals first**

   * Understanding SDLC
   * Folder structure
   * API design
   * Business logic
   * Error handling

2. **Avoid tool overload**

   * Git is important, but it should not distract from core backend learning in early stages.

3. **Industry reality**

   * Many freshers struggle not because of Git,
     but because they lack clarity in:

     * Design
     * Architecture
     * Responsibility separation

4. **Planned Git integration**

   * Git will be introduced after:

     * Phase 3 (Development) is stable
     * Code structure is finalized
   * This mirrors onboarding in many companies where code understanding comes before repo control.

---

## 🏗️ Project Structure

```
taskflow/
├── app.py                 # Application entry point
├── config.py              # Configuration settings
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
│
├── models/                # Database models
│   ├── user.py
│   └── task.py
│
├── routes/                # API routes
│   ├── auth.py
│   └── tasks.py
│
├── services/              # Business logic
│   ├── auth_service.py
│   └── task_service.py
│
├── utils/                 # Helper utilities
│   ├── security.py
│   └── logger.py
│
└── tests/                 # Unit tests
    ├── test_auth.py
    └── test_tasks.py
```

---

## ⚙️ Technologies Used

* Python 3
* Flask
* Flask-SQLAlchemy
* SQLite (can be extended to PostgreSQL)
* pytest

---

## 🔑 Core Features

### User Management

* User registration
* Secure password hashing
* User authentication

### Task Management

* Create task
* View tasks
* Update task
* Mark task as completed
* Delete task

### Security & Validation

* Password hashing
* Input validation
* Authorization checks (user can access only their own tasks)

---

## 🔁 SDLC Phases Followed

1. Requirement Analysis
2. System Design
3. Development
4. Testing
5. Deployment (planned)
6. Maintenance & Enhancements

---

## 🚀 Future Enhancements

* Git & GitHub workflow
* JWT-based authentication
* Dockerization
* PostgreSQL support
* Role-based access
* CI/CD pipeline

---

## 🧠 Learning Outcome

By building this project, the developer gains:

* Real backend engineering experience
* Understanding of SDLC in practice
* Confidence in designing REST APIs
* Industry-ready project for resume and interviews

---

## 📄 License

This project is for educational and learning purposes.
