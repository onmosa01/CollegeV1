# 📚 Student Information System Database

A relational Student Information System (SIS) database designed for Students, Faculty, and Admins to manage grades, enrollment, courses, rooms, and departments.

## Table of Contents

- [Role Features](#role-features)
  - [Students](#students)
  - [Faculty](#faculty)
  - [Admins](#admins)
- [Entity–Relationship Model](#entity–relationship-model)
  - [Diagram](#diagram)
  - [Key Tables](#key-tables)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Authors](#authors)

## Role Features

### Students

View grades and enrollment status.

### Faculty

Modify grades and enrollment for their students.

Manage courses they teach and course-room assignments.

### Admins

All Faculty permissions.

Manage rooms, departments, and user permissions.

Archive and update semesters.

## Entity–Relationship Model

The schema enforces role-based access, integrity, and scalability.

### Diagram

(Insert diagram exported from MySQL Workbench or link to `assets/`)

### Key Tables

- `user` – Authentication & link to student / employee.
- `student` – Admissions, graduation, enrollment link.
- `employee` – Faculty/Admin records with roles.
- `department` – Academic departments.
- `course` – Courses with credit hours.
- `section` – Course offerings, linked to faculty/students.
- `enrollment` – Tracks student enrollment status.
- `semester` – Current and archived academic terms.
- `room` / `building` – Physical classroom resources.
- Lookups – Employee roles, grades.

## Tech Stack

- Database: MySQL / MariaDB
- Modeling: MySQL Workbench (Forward Engineering)

## Setup

Clone the repository:

```powershell
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Import the .sql schema into MySQL Workbench.

Run the script to create tables and relationships.

## Authors

[Ayden Riddle](https://www.github.com/ayridd03)
[Nathan Mulholland](https://github.com/Beast1692)
[Onalenna Mosadi](https://github.com/onmosa01)
