# Description
- This project is a management system for a network of medical clinics, built with Java and MySQL.
- It handles employee scheduling, patient appointments, medical reports, and financial operations through a role-based access system with a user-friendly GUI.

# Features
- User Management: Role-based access for HR, medical staff, receptionists, and financial experts.
- Patient & Appointment Management: Schedule appointments, manage patient data, and generate medical reports.
- Financial Management: Calculate salaries, track clinic and individual doctor profits.
- Data Integrity: MySQL database with procedures for secure data handling and user authentication.
- Custom Views: Different user dashboards based on roles, e.g., doctors see patient lists, HR manages employee records.

# Project Structure
- Database: MySQL with tables for users, employees, patients, appointments, and more.
- Java Packages:
  - ConnectionPackage: Handles database connections and queries.
  - GUIPackage: Contains user interfaces for login, scheduling, and data management.
  - ModelsPackage: Data models for entities like User, Patient, Appointment.
