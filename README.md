Hospital Management System (SQL Project)

Project Overview

This project is a Hospital Management System designed using SQL. It provides a structured database for managing hospital operations, including tracking doctors, patients, appointments, and billing information. The system allows querying of essential healthcare data, making it a great learning experience for SQL development.

Database Schema

The database consists of four main tables:

Doctors

doctor_id (Primary Key)

first_name

last_name

specialty

phone_number

email

Patients

patient_id (Primary Key)

first_name

last_name

date_of_birth

gender

phone_number

email

address

Appointments

appointment_id (Primary Key)

doctor_id (Foreign Key references Doctors)

patient_id (Foreign Key references Patients)

appointment_date

reason_for_visit

status (e.g., scheduled, completed, canceled)

Billing

bill_id (Primary Key)

appointment_id (Foreign Key references Appointments)

total_amount

payment_status (e.g., paid, pending, canceled)

payment_date
