# 🚆 Train Reservation System (Java Web Application)

A full-stack **Train Ticket Reservation System** built using Java Servlets, JDBC, and SQL. This application allows users to search trains, check availability, book tickets, and manage reservations through a web interface.

---

## 📌 Features

### 👤 User Module

* User registration & login
* Search trains between stations
* Check seat availability
* Book train tickets
* View booking history
* Update profile & change password

### 🛠️ Admin Module

* Add new trains
* Update train schedules
* Delete/cancel trains
* View all trains and bookings

---

## 🏗️ Tech Stack

* **Backend:** Java (Servlets, JDBC)
* **Frontend:** HTML, CSS
* **Database:** Oracle SQL
* **Server:** Apache Tomcat
* **Build Tool:** Maven

---

## ⚙️ Project Architecture

The application follows a layered architecture:

* **Servlet Layer** → Handles HTTP requests & responses
* **Service Layer** → Business logic
* **DAO/Utility Layer** → Database interaction
* **Frontend** → HTML/CSS pages

---

## 🗄️ Database Setup

1. Create a new Oracle user:

```sql
CREATE USER RESERVATION IDENTIFIED BY MANAGER;
GRANT DBA TO RESERVATION;
```

2. Create required tables (refer to `Dummy-Database.md`)

3. Update database credentials in:

```
src/application.properties
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/prakhar27777/Train-Reservation-System.git
```

2. Import into Eclipse (Dynamic Web Project)

3. Configure Apache Tomcat Server

4. Build project using Maven:

```bash
mvn clean install
```

5. Deploy on Tomcat and run:

```
http://localhost:8080/Train-Ticket-Reservation-System
```

---

## ✨ Improvements & Enhancements

* Improved UI/UX for better usability
* Optimized database queries for faster response
* Modular code structure for scalability

---

## 🎯 Learning Outcomes

* Hands-on experience with Java Servlets & JDBC
* Understanding of MVC architecture
* Database design and integration
* Building real-world web applications

---

## 📌 Future Scope

* Convert to Spring Boot REST APIs
* Add JWT authentication
* Integrate payment gateway
* Deploy on cloud (AWS/Render)

---

## 👨‍💻 Author

**Prakhar Gupta**
📧 [prakharguptasdr123@gmail.com](mailto:prakharguptasdr123@gmail.com)
🔗 https://github.com/prakhar27777

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!
