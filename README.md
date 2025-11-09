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
    "email": "testuser@gmail.com",
    "phone": "908765498",
    "message": "This is a message"
  }
  ```
- **Success response (200)** — Returns the created object with timestamps and submitted data.
- UI behavior — Displays **"Form Submitted"** message upon successful API response.

---

