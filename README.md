# E-Commerce API Testing – Postman

## 📌 Project Overview
This is a mini API testing project created using **Postman** and **DummyJSON APIs**.
The project covers authentication, user, and product APIs
with validations for response status codes, response body, headers, data types, authentication tokens, and response time.

## 🛠️ Tools & Technologies
* Postman
* JavaScript (Postman Test Scripts)
* DummyJSON REST APIs

## 🔗 APIs Tested

### Authentication
* Login API – Used to authenticate the user and generate an access token.
* Get Authenticated User – Used the Bearer token to validate the authenticated user's details.

### User API
* Get Single User – Validated user details and response structure.

### Product APIs
* Get All Products – Validated product list, pagination details, and product data.
* Get Single Product – Validated product details, nested objects, reviews, and product data.

## ✅ Testing Performed
* Status code validation
* Response body validation
* JSON response validation
* Response header validation
* Mandatory field validation
* Data type validation
* Nested JSON object validation
* Authentication and Bearer token validation
* Response time validation
* Positive API testing

## 🔐 Authentication Flow

The Login API generates an `accessToken`.
The token is stored as a Postman environment variable and used as a Bearer token for the authenticated user API.

Login API
    ↓
Generate Access Token
    ↓
Store Token in Environment Variable
    ↓
GET /auth/me
    ↓
Bearer {{accessToken}}
    ↓
Validate Authenticated User

## 📚 Key Learning
This project helps gain hands-on experience in API testing using Postman,
including request/response validation, JavaScript-based test scripts, authentication using Bearer tokens,
environment variables, and basic API performance validation.
