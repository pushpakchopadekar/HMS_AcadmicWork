# HMS_AcadmicWork

# Hospital Management System

This repository contains the source code for a comprehensive Hospital Management System. This web-based application streamlines interactions between hospitals and patients, enabling efficient management of appointments, prescriptions, and patient data.

## Features

### For Patients
- **View Appointments:** Check past and upcoming appointments.
- **Access Prescriptions:** View and download prescription details.
- **Schedule Appointments:** Request new appointments based on doctor availability.
- **View Next Appointment Details:** Stay updated with the next scheduled visit.

### For Hospitals/Doctors
- **Manage Appointments:** Approve or reject patient requests for new appointments.
- **Patient Records:** Access and update patient details, medical history, and prescriptions.
- **Doctor Availability:** Update availability to manage scheduling efficiently.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## Installation

1. **Clone the repository:**
   ```bash
  https://github.com/pushpakchopadekar/HMS_AcadmicWork.git
   cd hospital-management-system
   ```

2. **Set up the database:**
   - Import the SQL file located in the `database/` directory into your MySQL server.
   - Update the database configuration in the `config.php` file with your database credentials:
     ```php
     $host = 'your-database-host';
     $dbname = 'your-database-name';
     $username = 'your-database-username';
     $password = 'your-database-password';
     ```

3. **Start the local server:**
   Use a tool like XAMPP, WAMP, or MAMP to run the PHP server. Place the project folder in the `htdocs` directory (or equivalent).

4. **Access the application:**
   Open a web browser and go to `http://localhost/hospital-management-system`.

## Folder Structure
- **`/assets`**: Contains CSS, JavaScript, and image files.
- **`/pages`**: Includes HTML/PHP files for various pages (e.g., login, dashboard, appointment management).
- **`/database`**: Includes the SQL script for setting up the database schema.
- **`/config.php`**: Contains database connection settings.

## Usage
1. **Login:** Separate login pages for patients and hospital staff.
2. **Dashboard:** Personalized dashboard for patients and doctors.
3. **Appointment Scheduling:** Patients can request new appointments; doctors can approve or reject them.



 
