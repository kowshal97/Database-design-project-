# Assignment 1 – Database Design

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Database](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Modeling](https://img.shields.io/badge/ERD-Logical%20%7C%20Physical-purple)

Database design project covering **two systems**:  
1. **Library Management System**  
2. **College Registration System**

This project includes **business definition, ERD modeling, logical & physical design, SQL implementation, and validation**.

---

## 📂 Deliverable
- [📥 Download Presentation (PPTX)](https://github.com/kowshal97/Lib and college/raw/main/Lib and college.pptx)

---

## 📌 Overview
The project demonstrates end-to-end database design using PostgreSQL.

### 🔹 Project Scope

#### 📚 Library Management System
- **Entities**: Book, Author, Genre, Member, Membership, Reservation, Checkout
- **Relationships**:
  - Book ↔ Author (M:N)
  - Book ↔ Genre (1:N)
  - Member ↔ Membership (1:N)
  - Member ↔ Checkout (Max 5 at a time)
  - Member ↔ Reservation (1:N)

#### 🏫 College Registration System
- **Entities**: Student, Course, Professor, Department, Enrollment, Prerequisite
- **Relationships**:
  - Student ↔ Enrollment (M:N)
  - Course ↔ Professor (M:1)
  - Course ↔ Department (M:1)
  - Course ↔ Prerequisite (self-referencing M:N)
  - Student ↔ Department (Major/Minor roles)

- **Database Design**: Logical and Physical models
- **SQL Implementation**: Table creation, inserts, and execution
- **Validation**: Query testing with sample data

---

## 🛠️ Tech Stack
- **PostgreSQL** (DDL + DML)
- **pgAdmin** for query execution
- **ERD Modeling** (draw.io / diagrams.net)

---

## 📸 Screenshots
*(Add images into a `diagrams/` folder later — these links will display them)*

- **Library ERD**  
  [![Library ERD](./diagrams/library-erd.png)](./diagrams/library-erd.png)

- **Library Logical Model**  
  [![Library Logical](./diagrams/library-logical.png)](./diagrams/library-logical.png)

- **College ERD**  
  [![College ERD](./diagrams/college-erd.png)](./diagrams/college-erd.png)

- **College Logical Model**  
  [![College Logical](./diagrams/college-logical.png)](./diagrams/college-logical.png)


---

## 🔗 Related Projects
- [Clinic Management System](https://github.com/kowshal97/clinic-management-database)  
- [Online Retail Store DB](https://github.com/kowshal97/Online-Retail-Store-database)

