# Airbnb Clone Backend - Requirements Specification

This document outlines the **functional** and **technical requirements** for the core backend features of the Airbnb Clone project.

---

## 1. User Authentication

### Overview
This module manages user registration, login, and authentication using secure password hashing and token-based access control (JWT).

### Functional Requirements
- Users must be able to register with a unique email address and password.
- Users must verify their email before accessing restricted resources.
- The system must authenticate users via JSON Web Tokens (JWT).
- Passwords must be stored securely using hashing (e.g., bcrypt).

### API Endpoints

| Endpoint | Method | Description | Authentication |
|-----------|--------|--------------|----------------|
| `/api/v1/auth/register/` | POST | Register a new user |  No |
| `/api/v1/auth/login/` | POST | Login with email & password |  No |
| `/api/v1/auth/logout/` | POST | Logout user | Yes |
| `/api/v1/auth/profile/` | GET | Get logged-in user profile | Yes |

### Input/Output Specifications

#### **Register**
**Input:**
```json
{
  "username": "stephen123",
  "email": "stephen@example.com",
  "password": "StrongPass123"
}
