Hospital Management System (HMS) - Database Schema
This is a simple hospital management system (HMS) database schema created using MySQL. The system is designed to manage patients, doctors, appointments, medical history, diagnoses, and schedules.

Database Structure
Tables:
Patient: Stores information about patients such as email, password, name, address, and gender.
MedicalHistory: Contains medical records for each patient including conditions, surgeries, and medications.
Doctor: Holds information about doctors including their name, email, gender, and password.
Appointment: Keeps track of appointments including the date, start time, end time, and status.
PatientsAttendAppointments: Links patients with appointments, including concerns and symptoms.
Schedule: Stores doctors' working schedules.
PatientsFillHistory: Links patients to their medical history records.
Diagnose: Records diagnoses and prescriptions made by doctors for each appointment.
DocsHaveSchedules: Associates doctors with their schedules.
DoctorViewsHistory: Allows doctors to view patients' medical history.
How to Use:
Database Setup:

Clone this repository or download the SQL file.
Run the SQL commands in a MySQL client to set up the database and tables.
Inserting Data:

The database includes sample data for patients, doctors, appointments, and other necessary entities.
Insert your own data using SQL INSERT statements or modify the existing ones.
Queries:

You can create custom queries to extract data from the tables, such as fetching patient history, upcoming appointments, etc.
Example Use Cases:
Patient Registration: Add new patients with their details like name, gender, address, etc.
Appointment Scheduling: Schedule appointments for patients and manage their concerns and symptoms.
Diagnosis Management: Doctors can diagnose patients during appointments and provide prescriptions.
Technologies:
MySQL Database
SQL for querying and managing data
