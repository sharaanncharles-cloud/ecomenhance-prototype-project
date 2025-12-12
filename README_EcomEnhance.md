 EcomEnhance – Unified E-Commerce Prototype

EcomEnhance is a prototype e-commerce platform built with **Python, Flask, HTML, CSS, JavaScript, and MySQL** to unify fragmented retail operations for small and medium retailers.  
It integrates both **customer shopping flows** and **admin workflows** into one lightweight, secure, and scalable system.

This project demonstrates product thinking (problem discovery → analysis → MVP → execution) and full-stack development skills.

 Supporting Images & Demo Video  
All project UI screenshots and the full application demo video are available here:

**Google Drive Folder:**  
https://drive.google.com/drive/folders/1uEwmIa7JNKrg56EgP9cHlE30U1JfXmMi?usp=sharing


 Overview
EcomEnhance was built to address a common challenge faced by small retailers:

 **Multiple disconnected tools leading to inefficiency, errors, and poor customer experience.**

The platform provides:
- A **unified customer journey** (Signup → Browse → Cart → Checkout)  
- A **comprehensive admin dashboard** for inventory, order management, discounts, reports, and analytics  

The prototype runs locally using **SQLite/MySQL** and is designed to scale to PostgreSQL or cloud deployment.

##  Key Features

###  Customer Panel
- User registration & login  
- OTP-secured password reset  
- Product catalog with search & filters  
- Cart management  
- Checkout with:
  - **Razorpay payment gateway**
  - **Cash on Delivery with OTP verification**

###  Admin Panel
- Dashboard with business insights  
- Order management & tracking  
- Customer management with loyalty tiers  
- Inventory and stock control  
- Discount/promo management  
- Review & rating insights  
- Automated **Excel exports** using Pandas  


##  Problem Statement

### 1. Fragmented Operations
Retailers use Excel, Razorpay, WhatsApp, and manual notes independently.

### 2. Customer Friction
Unreliable COD, clunky checkout, low trust.

### 3. Admin Inefficiency
Manual spreadsheets → errors, delays, limited insights.


##  Objectives
- Combine customer + admin journeys into one unified platform  
- Enable secure payments (Razorpay + COD OTP)  
- Automate Excel-based insights  
- Create a modular, scalable backend architecture  


##  SWOT Analysis

### **Strengths**
- Single unified system  
- Secure transactions  
- Automated insights  
- Scalable backend  

### **Weaknesses**
- Prototype stage  
- Dev OTP bypass  
- Basic UI  

### **Opportunities**
- Cloud release  
- Advanced dashboards  
- Multi-vendor expansion  

### **Threats**
- Established competitors  
- Trust barriers  
- Compliance requirements  

---

##  Proposed Solution

| Feature | Value | Feasibility | Scalability |
|--------|--------|-------------|-------------|
| Unified customer + admin platform | End-to-end workflow simplification | Modular Flask app | Cloud ready |
| Razorpay + COD OTP | Trust & fraud reduction | Integrated SDK | Multi-gateway support |
| Automated Excel reports | Saves admin time | Pandas backend | Real-time dashboards next |
| Cloud Deployability | Real-world usage | SQLite → PostgreSQL | AWS/Heroku deployable |


##  System Architecture
- **Backend:** Python (Flask), SQLAlchemy  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite/MySQL  
- **Payments:** Razorpay API  
- **Email/OTP:** Brevo (Sendinblue)  
- **Reports:** Pandas Excel exports  


##  Database Schema (ERD)
Includes key entities:
Users, Products, Orders, Order Items, Inventory, Discounts, Feedback, Payment Records.

(ERD image available in Google Drive)


##  Flow & Gantt Charts
- User Journey Flow  
- Admin Flow  
- Project Timeline (Gantt)  

(All diagrams available in the Drive folder)


##  Tech Stack

### Backend
- Python  
- Flask  
- SQLAlchemy  

### Frontend
- HTML5  
- CSS3  
- JavaScript  

### Database
- SQLite / MySQL  
- PostgreSQL-ready  

### Integrations
- Razorpay  
- Brevo (Sendinblue)  
- Pandas  


##  Future Enhancements
- Production-grade security  
- Full cloud deployment  
- Real-time dashboard analytics  
- Marketplace expansion  
- Mobile-friendly responsive UI  

---

##  Contact

**Shara Ann Charles**  
 Email: charlessharaann@gmail.com  
 Phone: +91 9880171196  
 LinkedIn: https://www.linkedin.com/in/shara-charles-4040321bb/

