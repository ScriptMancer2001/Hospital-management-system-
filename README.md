Hospital Management System:-

The Hospital Management System is a Python-based application integrated with MySQL to manage patient records efficiently. It streamlines the process of adding, retrieving, and updating patient information, making it ideal for small to medium-sized hospitals.

Features:-

Add Patient Records: Input and store patient details such as name, age, contact, and medical history.

View Records: Retrieve and display stored patient information.

Update Records: Modify existing patient details in the database.

Delete Records: Remove patient records securely when no longer needed.

Database Integration: Uses MySQL for robust and scalable data storage.

User-Friendly Interface: Simple and intuitive design for easy use.

Technologies and Libraries Used:-

Python: Core programming language.

MySQL: Database management system.

MySQL Connector: To establish a connection between Python and MySQL.

tkinter (optional): For GUI-based interaction (if implemented).

os: To manage file and system-level operations.

Installation

Clone the Repository:

git clone https://github.com/ScriptMancer2001/hospital-management-system.git
cd hospital-management-system

Install Dependencies:
Ensure you have Python 3 installed, then install the required libraries:

pip install mysql-connector-python

Setup MySQL Database:

Created a MySQL database named hospital_management .

Use the provided hospital_table.sql file to set up the necessary tables.

CREATE DATABASE hospital_management;
USE hospital_management;
CREATE TABLE patients (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    contact VARCHAR(15),
    medical_history TEXT
);

Run the Application:

python hospital_management.py

Usage

Launch the system by running the script.

Select an operation from the menu (e.g., add patient, view records, update records).

Follow the prompts to complete the desired operation.

Project Structure

hospital-management-system/
├── hospital_management.py  # Main script for the application
├── requirements.txt        # List of dependencies
├── hospital_table.sql      # SQL file for database setup
├── README.md               # Project documentation
└── resources/              # Additional resources (if any)

Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository, make changes, and submit a pull request.



Acknowledgments

Thanks to the developers of Python and MySQL for providing robust tools for application development.

Special thanks to the open-source community for inspiration and support.

