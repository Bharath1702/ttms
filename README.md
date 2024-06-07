# Timetable Management System

## Overview
The Timetable Management System is a web-based application designed to manage and schedule timetables efficiently. This system is built using HTML, CSS, JavaScript, PHP, and MySQL, providing a comprehensive solution for creating, updating, and managing academic timetables.

## Features
- **User Authentication:** Secure login for admin and users.
- **Dynamic Timetable Creation:** Easily create and modify timetables.
- **Responsive Design:** User-friendly interface adaptable to various devices.
- **Database Management:** Efficient storage and retrieval of timetable data using MySQL.
- **Error Handling:** Robust error handling and validation mechanisms.

## Technologies Used
- **Frontend:**
  - HTML: For structuring the web pages.
  - CSS: For styling the web pages.
  - JavaScript: For interactivity and dynamic behavior.

- **Backend:**
  - PHP: For server-side scripting and database interaction.
  - MySQL: For database management.

## Installation and Setup
### Prerequisites
- Web server (e.g., Apache)
- PHP (v7.0 or higher)
- MySQL

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/bharath1702/ttms.git
2. **Navigate to the project directory:**
   ```bash
   cd ttms
3. **Set up database:**
   ```bash
   mysql -u your_username -p your_database < ttms.sql
4. **Configure Database:**
   ```bash
   <?php
$servername = "localhost";
$username = "your_username";
$password = "your_password";
$dbname = "your_database";
?>
5. **Start the Server:**
  * Place the project files in the web server’s root directory (e.g., htdocs for XAMPP).
  * Start the Apache and MySQL services using your web server control panel.

PROJECT STRUCTURE
ttms/files/
│
├── assets/                             # Directory for static assets (images, styles, scripts, etc.)
│   ├── css/
│   │   └── style.css                   # Main stylesheet
│   ├── js/
│   │   └── main.js                     # Main JavaScript file
│   └── images/
│       └── logo.png                    # Example image file
│
├── graphql/                            # Directory for GraphQL schema and resolvers
│   ├── schema.graphql                  # GraphQL schema definition
│   └── resolvers/
│       ├── classroomResolvers.js       # Resolvers for classroom operations
│       ├── subjectResolvers.js         # Resolvers for subject operations
│       ├── teacherResolvers.js         # Resolvers for teacher operations
│       └── allotmentResolvers.js       # Resolvers for allotment operations
│
├── public/                             # Public directory accessible by web server
│   ├── index.html                      # Home page
│   ├── login.html                      # User login page
│   ├── dashboard.html                  # Admin dashboard
│   ├── create_timetable.html           # Timetable creation page
│   └── view_timetable.html             # View timetable page
│
├── src/                                # Source directory for PHP files
│   ├── addclassroomFormValidation.php  # Form validation for adding classroom
│   ├── addclassrooms.php               # Add classrooms script
│   ├── addsubjectFormValidation.php    # Form validation for adding subject
│   ├── addsubjects.php                 # Add subjects script
│   ├── addteacherFormValidation.php    # Form validation for adding teacher
│   ├── addteachers.php                 # Add teachers script
│   ├── adminFormvalidation.php         # Admin form validation
│   ├── adminform.php                   # Admin form script
│   ├── algo.php                        # Algorithm script
│   ├── allotclasses.php                # Allot classes script
│   ├── allotmentFormvalidation.php     # Form validation for allotment
│   ├── allotmentpracticalFormvalidation.php # Practical allotment form validation
│   ├── allotpracticals.php             # Allot practicals script
│   ├── allotsubjects.php               # Allot subjects script
│   ├── assignSubstituteFormValidation.php # Form validation for assigning substitute
│   ├── connection.php                  # Database connection script
│   ├── curl.php                        # CURL script
│   ├── deleteallotment.php             # Delete allotment script
│   ├── deleteclassroom.php             # Delete classroom script
│   ├── deletesubject.php               # Delete subject script
│   ├── deleteteacher.php               # Delete teacher script
│   ├── facultyformvalidation.php       # Faculty form validation
│   ├── facultypage.php                 # Faculty page script
│   ├── func.php                        # General functions script
│   ├── generatetimetable.php           # Generate timetable script
│   ├── getcellindex.php                # Get cell index script
│   ├── send.php                        # Send script (for notifications or similar)
│   ├── sms.php                         # SMS sending script
│   ├── studentvalidation.php           # Student validation script
│   └── index.php                       # Main index file
│
├── config.php                          # Database configuration file
├── timetable.sql                       # SQL file for setting up the database schema
├── server.js                           # Node.js server file for GraphQL (optional, if using Node.js)
├── package.json                        # Node.js package file (if using Node.js)
└── README.md                           # Project README file

##License
This project is licensed under the MIT License - see the LICENSE file for details.

