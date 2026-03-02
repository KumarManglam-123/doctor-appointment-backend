# Doctor Appointment Backend

This repository contains the database design and ER diagram for the Doctor Appointment Backend system.

##  Task 1 – ER Diagram

A normalized relational database structure (3NF) was designed with the following highlights:

- Central `users` table for authentication and role management
- One-to-One relationship: Users → Doctors
- One-to-One relationship: Users → Patients
- Many-to-Many relationship: Doctors → Specializations
- `appointments` acts as a bridge between Doctor and Patient
- `slots` manage doctor availability
- `payments`, `feedbacks`, and `patient_details` linked 1:1 with appointments
- Proper indexing for scalability

The ER Diagram is available inside the `docs` folder.

---

Created as part of internship backend task submission.
