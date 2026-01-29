
# Airline Reservation System – SQL Database Project
A comprehensive SQL-based airline reservation system designed to manage passengers, flights, bookings, payments, schedules, and crew information using relational database concepts.

---

## 2. Short Description / Purpose

The Airline Reservation System is an SQL-driven project that simulates a real-world airline database. It enables efficient storage, retrieval, and management of airline operations such as passenger bookings, flight scheduling, payments, and crew assignments while demonstrating core and advanced SQL concepts.

---

## 3. Tech Stack

The project was built using the following tools and technologies:

* 🗄 **MySQL** – Relational database management system
* 🧠 **SQL (DDL & DML)** – Table creation, constraints, and queries
* 🔗 **Joins & Subqueries** – Data retrieval across multiple tables
* 📐 **ER Diagram** – Visual representation of database relationships
* 🧪 **SQL Functions & Constraints** – Primary keys, foreign keys, checks, and uniqueness
* 📁 **File Format** – `.sql` scripts and `.png` screenshots for documentation

---

## 4. Data Source

**Source:** Manually designed and simulated dataset

**Database Name:** `Airline_data`

### Database Structure Includes:

* Passengers
* Flights
* Aircrafts
* Schedules
* Bookings
* Payments
* Crew
* Reservations

The schema is normalized and designed to reflect real airline reservation workflows.

---

## 5. Features / Highlights

### • Business Problem

Airlines must manage complex relationships between passengers, flights, schedules, payments, and resources. Handling this data manually or without proper structure can lead to inefficiency, data inconsistency, and errors.

Key challenges include:

* Managing passenger and booking details accurately
* Tracking flight schedules and aircraft assignments
* Handling payments and reservation statuses
* Querying complex relationships across multiple entities

---

### • Goal of the Project

To design and implement a structured SQL database that:

* Simulates a real-world airline reservation system
* Demonstrates strong understanding of **database design and normalization**
* Showcases **SQL querying skills** from basic to advanced level
* Enables efficient data retrieval using joins, subqueries, and constraints

---

### • Walkthrough of Key Components

#### 📌 ER Diagram

* Visualizes relationships between entities such as **Passengers, Flights, Bookings, Payments, Aircrafts, and Schedules**
* Clearly defines **primary keys and foreign key relationships**

---

#### 🗄 Database & Tables

* Creation of the `Airline_data` database
* Structured tables with constraints:

  * `PRIMARY KEY`
  * `FOREIGN KEY`
  * `UNIQUE`
  * `CHECK`
  * `NOT NULL`

---

#### 🧱 Data Definition Language (DDL)

* Tables created for:

  * **Passengers** – Stores personal and contact details
  * **Flights** – Flight number, route, timings, duration
  * **Aircrafts** – Model, manufacturer, capacity
  * **Schedules** – Flight-aircraft mapping and seat availability
  * **Bookings** – Passenger bookings and booking status
  * **Payments** – Payment amount, method, and date

---

#### 🔍 SQL Queries & Operations

##### ✔ UNION

* Retrieve passenger IDs with **confirmed or cancelled bookings**

##### ✔ Joins

* **INNER JOIN** – Passenger details with bookings
* **LEFT JOIN** – All passengers including those without bookings
* **RIGHT JOIN** – All bookings including missing passenger details
* **FULL JOIN** – Complete passenger-booking mapping
* **CROSS JOIN** – All possible passenger-flight combinations
* **SELF JOIN** – Flights with same source city but different destinations

---

##### ✔ Subqueries

* Single-row subqueries to:

  * Identify passengers with the **earliest booking**
  * Extract filtered booking and passenger insights

---

## 6. Business Impact & Learning Outcomes

* **Database Design Skills:** Strong understanding of normalization and relationships
* **Query Optimization:** Efficient data retrieval using joins and subqueries
* **Real-World Simulation:** Mirrors airline reservation workflows
* **Problem-Solving:** Ability to translate business requirements into SQL logic
* **Portfolio Ready:** Demonstrates practical SQL expertise for data analyst and database roles

---

## 7. Screenshots / Demo

📷 **Project Screenshots Include:**
(https://github.com/Vikrant123-vik/SQL-Project-Airline-Reservation-System-/blob/main/Snapshot1%20of%20SQL%20Dashboard.png)
(https://github.com/Vikrant123-vik/SQL-Project-Airline-Reservation-System-/blob/main/Snapshot2%20of%20SQL%20Dashboard.png)
()


