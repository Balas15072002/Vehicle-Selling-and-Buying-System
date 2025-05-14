# Wheelsy – Vehicle Selling and Buying System

**Type:** B2B (Business-to-Business)  
**Target Audience:**  
- Showroom Managers  
- Vehicle Sellers (New & Used)

**Timeline:** Approximately 1 Month  
**Budget:** ₹3,00,000 (3 Lakhs)  
**Team Size:** 1 Members  

---

## Project Overview

Wheelsy is a full-featured vehicle selling and buying system tailored for vehicle showrooms and registered sellers. It allows admins to manage both new and used vehicles, monitor availability, apply discounts, and handle customer feedback efficiently.

---

## Key Features

### Admin Access
- Secure registration and login with role-based access
- Add, update, or remove vehicle details (new and used)
- Set vehicle availability (In Stock / Out of Stock)
- Manage discounts for specific vehicles

### Vehicle Listings
- View detailed vehicle information
- Search and filter by brand, type, price, and vehicle condition (used/new)

### Customer Support
- Access customer reviews and feedback

---

## Model Classes

### 🔹 Admin
- int adminid  
- String name  
- String email  
- long contact  
- int age  
- String password  
- String current_password  

### 🔹 User
- int userid  
- String name  
- String email  
- long contact  
- int age  
- LocalDate date_of_birth  
- String address  

### 🔹 Vehicle
- int vehicleid  
- String brand  
- String model  
- boolean isUsed  
- String color  
- String milage  
- double price  
- String vehicle_type  
- boolean inStock  
- double discount  

### 🔹 Review
- String customerName  
- String feedback  

---
