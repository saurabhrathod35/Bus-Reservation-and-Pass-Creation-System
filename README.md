#  Bus-Reservation-and-Pass-Creation-System
![Screen shots](https://cloud.githubusercontent.com/assets/22594110/24895423/2a5eaa08-1e45-11e7-8cd3-3f5d51cf54da.gif)

A web-based application that allows users to **book bus tickets** and **generate monthly passes** online — eliminating the need to visit a bus terminal. The system provides separate interfaces for users and admins, streamlining the operations of public transportation.

## 🔍 Overview

This system is useful for:
- Booking bus tickets quickly and securely
- Creating and renewing monthly passes
- Managing buses, routes, schedules, and reservations
- Admin oversight and reporting

## ⚙️ Technologies Used

| Layer         | Technology                |
|---------------|---------------------------|
| Frontend      | HTML, Bootstrap, jQuery   |
| Backend       | JSP, Servlet              |
| Database      | MySQL                     |
| Architecture  | MVC (Model-View-Controller) |
| Development   | Eclipse IDE               |
| Server        | Apache Tomcat 7           |

## 💡 Key Features

### 👤 User Features
- Register/Login with secure credentials
- Book bus tickets by selecting route and time
- View, cancel, or print booked tickets
- Generate monthly passes (for regular travelers)

### 🛠️ Admin Features
- Add and manage buses, routes, and timings
- View and manage bookings and passes
- Monitor user activity
- System reports and data insights

## 🗃️ Database Tables

- `users` – stores user information
- `buses` – contains bus details
- `routes` – origin/destination and timing
- `bookings` – reservation records
- `passes` – monthly pass info

The SQL schema is provided in the `/database` directory.

## 📸 Screenshots

> *(Include screenshots of: login screen, booking form, pass generation, admin panel, etc.)*

## 🚀 How to Run the Project

### ✅ Prerequisites

- Java JDK 8+
- MySQL Server
- Eclipse IDE
- Apache Tomcat 7 or above

### 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/saurabhrathod35/Bus-Reservation-and-Pass-Creation-System.git
