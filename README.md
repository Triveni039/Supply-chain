# 🥦 Vegetable Market Management System

A **Python-based console application** for managing a vegetable market.  
This project provides **role-based access** (Owner & User), handles inventory, billing, discounts, and generates invoices with revenue reports.

---

## 🚀 Features

### 👨‍💼 Owner (Admin)
- 🔐 Secure login with admin credentials  
- ➕ Add new vegetables with quantity, cost price, selling price, and MRP  
- ➖ Remove vegetables from inventory  
- ✏️ Update quantity, prices, and MRP of existing vegetables  
- 👥 View customer purchase details  
- 📊 Generate sales reports and profit/loss calculations  
- 💰 Track total revenue and cost  

### 🛒 User
- 📋 View available vegetables and prices  
- 🛍️ Add items to cart, update or remove them  
- 🧾 Get detailed invoice with:
  - Invoice number and timestamp  
  - MRP, discount applied, selling rate, and final amount  
- 📱 Mobile number validation (must start with 6/7/8/9 and be 10 digits)  
- 💳 Choose payment method (Cash or UPI)  
- ✅ Receipt shared on screen after billing  

---

## 🛠️ Tech Stack
- **Language:** Python 3.11  
- **Modules:** `datetime` (for invoice generation)  
- **Interface:** Console (Text-based)

