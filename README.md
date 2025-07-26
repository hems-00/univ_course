# University Course Registration System

## Project Overview

The University Course Registration System is designed to streamline the process of course enrollment for students and administrative management of course allocations. The system enables students to register for courses, manage their schedules, and handle waiting lists dynamically. Administrators can oversee course allocations, seat availability, and user management.


---

## Objectives

### Streamline Course Registration
- Simplify the process for students to register for courses, select preferred sections, and manage their course schedules.
- Ensure that the system is user-friendly, intuitive, and accessible.

### Efficient Seat Management
- Provide real-time updates on seat availability to avoid over-enrollment.
- Implement a fair and transparent waiting list system.

### Administrative Oversight
- Enable administrators to manage course offerings, allocate seats, and oversee user accounts effectively.
- Generate reports and analytics to assist in academic planning and resource allocation.

---

## Key Components

### User Registration and Authentication
- **Secure Accounts** with password protection and encryption.
- **Role-Based Access** for students and administrators.

### Course Selection and Enrollment
- **Listings** with descriptions, prerequisites, instructors, and sections.
- **Real-Time Enrollment** with feedback on seat availability.

### Add and Drop Courses
- Students can add/drop courses flexibly.
- Prerequisites are verified before enrollment.

### Waiting List Management
- **Dynamic Ranking** using criteria like CGPA, hackathon wins, and internships.
- **Automatic Seat Allocation** from the waiting list.

### Administrative Controls
- **Course Management**: add, modify, delete, manage seats and waitlists.
- **User Management**: add/remove users, reset passwords.
- **Reporting**: on enrollment, seat usage, and waiting lists.

---

## Installation and Setup

### Prerequisites
- Code::Blocks IDE (with built-in C compiler)
- Required CSV files

### Required CSV Files
1. `core_courses.csv`
2. `course_seats.csv`
3. `Design Thinking_waiting_list.csv`
4. `Elective_courses.csv`
5. `Applied Mathematics_waiting_list.csv`
6. `Data Architecture_waiting_list.csv`
7. `Data Science_waiting_list.csv`
8. `Film Appreciation_waiting_list.csv`
9. `Machine Learning_waiting_list.csv`
10. `Psychology_waiting_list.csv`
11. `Robotics_waiting_list.csv`
12. `Theoretical Physics_waiting_list.csv`
13. `reallocated_students.csv`
14. `users.csv`
15. `user_coursechoices.csv`

---

## Usage in the Project

- Core and Elective course info comes from `core_courses.csv` and `elective_courses.csv`.
- `course_seats.csv` manages seat allocation and over-enrollment.
- Each course has its own waitlist CSV file (e.g., `Design Thinking_waiting_list.csv`).
- Student info is stored in `users.csv`.
- `user_coursechoices.csv` contains student course preferences.
- `reallocated_students.csv` handles course reassignments.

---

## Usage

### Running the Program
- Open in Code::Blocks
- Build and Run the project

### User Guide

#### Student:
- Register account with name, ID, password, etc.
- Login with credentials.
- Select, add, drop courses.
- View waitlist position.

#### Admin:
- Manage courses and user accounts.
- Modify seat availability and system settings.

---

## Limitations and Future Enhancements

### Current Limitations
- No CGPA verification.
- Prerequisites not strictly checked.
- Supports only one semester at a time.

### Future Enhancements
- Integration with academic databases.
- Multi-semester planning support.
- Enhanced user interface (UI/UX).


