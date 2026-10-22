# 🚀 Restful-Booker API Automation & SQA Testing Suite

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-2A2A2A?style=for-the-badge&logo=npm&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

This repository contains a comprehensive API Test Automation and Manual Testing suite built for the **Restful-Booker** API. The project demonstrates end-to-end API testing workflows, including test collections, environment configurations, automated execution via **Newman**, and detailed HTML reporting.

---

## 🚀 Project Overview

* **Target API:** [Restful-Booker Heroku App](https://restful-booker.herokuapp.com/)
* **Testing Tools:** Postman, Newman, JavaScript (Chai assertions)
* **Test Coverage:** Authentication, CRUD Operations (Create, Read, Update, Partial Update, Delete), Health Check, Schema/Data Type Validation, and Negative Testing.

---

## 🛠️ Tech Stack & Tools

* **API Testing & Client:** Postman
* **Command-Line Runner:** Newman
* **Reporting:** Newman HTML Extra / Summary Reporter
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```text
├── Booking_Collection.postman_collection.json  # Postman Collection containing all API requests & tests
├── Booking_Environment.postman_environment.json # Environment variables (Base URL, Tokens, IDs)
├── Booking_Collection-2026-10-22-12-32-17-662-0.html # Detailed Newman HTML Execution Report
└── README.md                                   # Project Documentation
