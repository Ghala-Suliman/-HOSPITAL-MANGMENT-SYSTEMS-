#  HOSPITAL MANGMENT SYSTEMS 
 This is a hospital management user interface for managing, monitoring and controlling the system in a Hospital. This application is developed in java, which mainly focuses on basic operations in a hospital like adding new patient information, and updating new information, assigning the doctor for patient. It features a familiar and well thought-out, an attractive online user interface, combined with strong searching Insertion and reporting capabilities. The Backend of the project is designed with Java, MySQL for database connectivity and front end using HTML, CSS, and Bootstrap.
  HOSPITAL MANGMENT SYSTEMS  The Hospital Management System is an integrated software solution designed to improve the administrative, financial, and medical operations in hospitals, facilitating access to patient information and enhancing the quality of healthcare.

  Core Components

1. Java Servlets (Backend)
   - Admnlogin Servlet:
     - Handles admin login functionality. It checks the entered username and password, and if correct, forwards the admin to the admin dashboard.
   - Doclogin Servlet:
     - Manages the login process for doctors. The servlet checks the doctor's credentials against the database and redirects them to their dedicated page if the credentials are valid.
   - Plogin Servlet:
     - Handles the login for patients. It validates patient credentials by comparing them with stored data in the patients_info table, and then redirects the patient to their page.

2. MySQL Database (Database Layer)
   - Patients Table (`patients_info`):
     - Stores patient details such as name, contact number, email, and aadhar. This table is crucial for managing patient information and verifying login credentials for patients.
   - Doctors Table (`doc_info`):
     - Contains doctor information such as name, specialization, and password. It allows the system to authenticate doctors and store information about their specializations.
   - Appointments Table (`apn_info`):
     - Stores appointment data including the patient name, doctor name, specialization, appointment date, and time. This table is essential for scheduling and managing appointments between doctors and patients.

3. JSP Pages (Frontend)
   - adminpage.jsp: The admin dashboard where admins can manage hospital data like doctors and appointments.
   - docpage.jsp: A doctor’s page where they can see their scheduled appointments and check patient details.
   - patientpage.jsp: The patient’s page where they can see their personal information and upcoming appointments.
   
4. JDBC (Database Connectivity)
   - JDBC (Java Database Connectivity) is used to connect the servlets to the MySQL database, allowing the application to execute SQL queries for login verification, retrieving data, and managing appointments.
  
   - System Architecture:
   - ![Hospital Management System](https://github.com/Ghala-Suliman/-HOSPITAL-MANGMENT-SYSTEMS-/blob/main/Hospital%20mangment%20system.png?raw=true)


