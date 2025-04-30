# 🧪 JMeter API Testing - Assignment 2

This project contains a JMeter test plan designed to simulate and test RESTful API endpoints for performance, correctness, and functional validation. The test plan includes multiple samplers and assertions to ensure reliable API behavior under different conditions.

---

## 🎯 Objective

- Perform API testing using Apache JMeter
- Validate response time, status codes, and data correctness
- Simulate realistic user interactions with HTTP requests
- Use assertions and variables to automate API verification

---

## 🛠️ Tools & Technologies

- **Apache JMeter** (v5.x or above)
- **HTTP Request Sampler**
- **JSON Extractor**
- **Response Assertions**
- **User-Defined Variables**
- **View Results Tree & Summary Report**

---

## 📂 Test Plan Structure

Below is a general structure inferred from standard test plans:

### 🧵 Thread Group
Simulates concurrent users (can be configured for load testing)

### 📡 HTTP Request Samplers
- **GET** requests to fetch resources (e.g., books, users, products)
- **POST** requests to create resources (e.g., orders, users)
- **PUT/PATCH** to update data
- **DELETE** to remove resources

### 🔧 Configuration Elements
- **HTTP Header Manager** – Sets content-type to `application/json`
- **User-Defined Variables** – Base URL, token, user ID, etc.

### 🔍 Post-Processors
- **JSON Extractor** – Extracts data like `orderId` or `token` from response

### ✅ Assertions
- **Response Assertion** – Ensures correct HTTP status codes (e.g., 200, 201)
- **Duration Assertion** – Optional, to assert performance limits

---

## 📈 Key Features

- Automated JSON data extraction
- Status and content validation
- Dynamic data-driven testing
- Modular test structure for reusability

---
## 👩‍💻 Author

**Hafsa Farhan**  
Software Engineering Student |QA Intern| 10Pearls Pakistan

---
## 📅 Date
30 April 2025

