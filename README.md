# 🚂 Railway Management System

**Live Demo**: [https://pieljay.infinityfreeapp.com](https://pieljay.infinityfreeapp.com)

> **University Database Project** - Advanced full-stack railway management system demonstrating complex database design and real-world constraint handling.

---

## 📋 Project Overview

This project simulates a **fictional single-track railway company** management system, tackling the complex challenge of coordinating train movements on shared infrastructure while providing a complete booking and payment experience.

### 🎯 Core Challenge
Managing a **54km single-track railway line** where trains must coordinate movements to prevent collisions, requiring:
- Real-time conflict detection and resolution
- Dynamic scheduling algorithms
- Advanced database triggers and constraints
- Multi-system integration

---

## ✨ Key Features

### 🚄 **SFT Railway Platform** (`/Prova1/`)
- **Smart Booking System**: Real-time seat allocation with conflict prevention
- **Multi-Role Authentication**: Three distinct user types with tailored interfaces
- **Train Scheduling**: Dynamic timetable management with single-track coordination
- **Interactive Maps**: Visual station selection and route planning
- **Responsive Design**: Mobile-first approach with Bootstrap 5

### 💳 **PS Gateway** (`/Prova2/`)
- **Secure Payment Processing**: RESTful API for transaction handling
- **Merchant Dashboard**: Analytics and transaction management
- **Balance Management**: Real-time account updates via AJAX calls

---

## 👥 User Roles & Capabilities

### 🎫 **Passengers (Utenti)**
```
✅ Search and book train tickets
✅ View and modify existing reservations  
✅ Real-time seat selection
✅ Payment processing integration
✅ Booking history and receipts
```

### ⚙️ **Operations Staff (Esercizio)**
```
🔧 Compose and manage train formations
🔧 Create and modify timetables
🔧 Fleet management and maintenance scheduling
🔧 Real-time service planning
🔧 Handle booking requests and conflicts
```

### 📊 **Administrators (Admin)**
```
📈 Revenue analytics and profitability reports
📈 Occupancy rates and performance metrics
📈 User management and system oversight
📈 Service approval workflows
📈 Comprehensive system monitoring
```

---

## 🏗️ System Architecture

### **Two-System Design**
```
┌─────────────────┐    HTTP/cURL     ┌──────────────────┐
│   SFT Railway   │ ◄────────────► │  PaySteam API    │
│   Platform      │   JSON/REST     │   Gateway        │
│   (Prova1)      │                 │   (Prova2)       │
└─────────────────┘                 └──────────────────┘
```

The railway booking system communicates with the payment gateway through secure API calls, creating a seamless user experience while maintaining system separation.

---

## 💻 Technology Stack

| Component | Technology |
|-----------|------------|
| **Backend** | PHP 8.3+ |
| **Database** | MySQL/MariaDB |
| **Frontend** | Bootstrap 5.3.7 |
| **JavaScript** | Vanilla JS + jQuery |
| **Icons** | Font Awesome 6.7.2 |
| **Charts** | Chart.js 4.5.0 |
| **Tables** | DataTables 2.3.2 |

---

## 🎮 Demo Accounts

Try the system with these demo accounts:

| Role | Username | Password | Access Level |
|------|----------|----------|--------------|
| **Passenger** | `demo_user` | `demo123` | Booking & Reservations |
| **Operations** | `demo_ops` | `ops123` | Fleet & Scheduling |
| **Admin** | `demo_admin` | `admin123` | Full System Access |

---

## 📸 System Overview

### Railway Platform Dashboard
```
🎫 Passenger Interface    ⚙️ Operations Panel     📊 Admin Analytics
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│ Search Trains   │     │ Fleet Manager   │     │ Revenue Charts  │
│ Book Tickets    │     │ Schedule Editor │     │ User Reports    │
│ My Bookings     │     │ Conflict Alerts │     │ System Metrics  │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

### Payment Gateway
```
💳 PaySteam Dashboard           🏪 Merchant Panel
┌─────────────────────────┐    ┌─────────────────────────┐
│ Transaction Processing  │    │ Revenue Analytics       │
│ Balance Management      │    │ Payment History         │
│ User Account System     │    │ Account Management      │
└─────────────────────────┘    └─────────────────────────┘
```

---

## 🔧 Advanced Features

### **Single-Track Management**
The system implements sophisticated algorithms to handle train movements on shared tracks, preventing conflicts through:
- Real-time scheduling validation
- Automatic conflict detection
- Dynamic route optimization
- Emergency rescheduling capabilities

### **Real-time Seat Management**
Dynamic seat allocation system that:
- Prevents overselling through live inventory tracking
- Handles concurrent booking requests
- Manages seat preferences and accessibility needs
- Provides instant availability updates

### **Payment Integration**
Seamless communication between railway and payment systems:
- Secure API communication
- Real-time transaction processing
- Multiple payment method support
- Automatic refund handling

---

## 🛡️ Security Features

- **SQL Injection Prevention**: Comprehensive input sanitization
- **CSRF Protection**: Token-based form validation
- **Session Management**: Secure authentication system
- **Role-Based Access**: Granular permission controls
- **Data Encryption**: Sensitive information protection

---

## 🎓 Educational Context

This project was developed as part of a **Database Systems course**, demonstrating:

### **Key Learning Objectives**
✅ Complex database schema design with real-world constraints  
✅ Multi-user system architecture and role management  
✅ API development and inter-system communication  
✅ Real-time conflict resolution algorithms  
✅ Full-stack web development with modern technologies  

### **Database Concepts Demonstrated**
- Advanced normalization and relationship design
- Trigger-based business logic implementation
- Transaction management and ACID compliance
- Performance optimization techniques
- Complex constraint handling

---

## 🌟 Project Highlights

### **Single-Track Railway Challenge**
The core complexity of this project lies in managing a single-track railway where trains traveling in opposite directions must coordinate to avoid collisions. This real-world constraint required:

- **Sophisticated scheduling algorithms**
- **Real-time conflict detection**
- **Dynamic route planning**
- **Emergency handling procedures**

### **Multi-System Integration**
Demonstrates enterprise-level system design with:
- **Microservices architecture** (Railway + Payment systems)
- **RESTful API communication**
- **Transaction synchronization** across systems
- **Error handling and rollback** mechanisms

---

## 📝 Technical Notes

- **Language**: Interface is in Italian (university project requirement)
- **Payment System**: Simplified implementation for educational purposes
- **Single-Track Logic**: Primary focus demonstrating database complexity

---

## 🔗 Resources

- **Live Demo**: [https://pieljay.infinityfreeapp.com](https://pieljay.infinityfreeapp.com)
- **Database Schemas**: 
  - [SFT Railway ERD](https://pieljay.infinityfreeapp.com/Documentazione/SLR_CROW_Prova1.php)
  - [PaySteam ERD](https://pieljay.infinityfreeapp.com/Documentazione/SLR_CROW_Prova2.php)

---

## 🎯 System Capabilities

### **For Railway Operations**
- Complete train fleet management
- Real-time scheduling and conflict resolution
- Passenger booking and payment processing
- Comprehensive reporting and analytics
- Multi-role user management

### **For Payment Processing**
- Secure transaction handling
- Merchant dashboard with analytics
- Multi-currency and payment method support
- Integration-ready API design
- Compliance with security standards

---

*This project showcases advanced database design principles applied to a real-world transportation management scenario, demonstrating both technical complexity and practical application.*

---

## 🚂 Getting Started

**Note**: Trains might be missing from the schedule! To fully test the website, first log in as an **Operations (Esercizio)** user and create some trains and timetables. Then you can test the passenger booking system. Enjoy! :)
