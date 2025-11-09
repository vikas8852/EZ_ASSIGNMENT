#  Varnan Assignment — React + Tailwind + API Integration

This repository contains a fully responsive, single-page React application (portfolio/home page) built to match a Figma design and integrated with a backend contact API.  
The project includes form validation, API integration, horizontal page scrolling, Framer Motion animations, and responsive layouts for all devices.

## Project Overview

This project is a front-end implementation of the **Varnan home page**, featuring a clean, responsive, and animated design based on the provided Figma reference.

## 🔗 API Integration Details

- **Endpoint:** `POST ${process.env.REACT_APP_API_URL}`
- **Request Example:**
  ```json
  {
    "name": "Test User",
    "email": "testuser123@gmail.com",
    "phone": "88984524",
    "message": "This is a messeage"
  }
  ```
- **Success response (200)** — Returns the created object with timestamps and submitted data.
- Expected Response (200)
```{
  "created_at": "2025-11-8T05:27:59.371578Z",
  "email": "testuser@gmail.com",
  "id": 49,
  "message": "This is a message",
  "name": "Test user",
  "phone": "908765498",
  "updated_at": "2025-10-10T05:27:59.371598Z"
}````



