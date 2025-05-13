
# Clinic Booking System - MySQL Database#
# 📌 Overview #
This is a simple and complete MySQL database project designed for managing a clinic booking system. It includes functionalities to handle:

Patient records

Doctor records and specialties

Clinic rooms

Appointments and doctor schedules

Payments

Medications and prescriptions

System users with roles (admin, doctor, receptionist)

# Database Structure #

| Table Name        | Description                                    |
| ----------------- | ---------------------------------------------- |
| `Specialties`     | List of medical specialties                    |
| `Doctors`         | Doctor details and linked specialty            |
| `Patients`        | Stores patient information                     |
| `Clinic_Rooms`    | Room numbers and types                         |
| `Appointments`    | Appointment data, linking doctors and patients |
| `Payments`        | Payment records tied to appointments           |
| `Users`           | System user accounts and roles                 |
| `Medications`     | Medication names and descriptions              |
| `Prescriptions`   | Linked to appointments and medications         |
| `Doctor_Schedule` | Weekly working hours for each doctor           |
