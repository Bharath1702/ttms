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
   $servername = "localhost";
   $username = "your_username";
   $password = "your_password";
   $dbname = "your_database";
   
5. **Start the Server:**
  * Place the project files in the web server’s root directory (e.g., htdocs for XAMPP).
  * Start the Apache and MySQL services using your web server control panel.

PROJECT STRUCTURE
ttms/files/
<br>
│
<br>
├── assets/                             # Directory for static assets (images, styles, scripts, etc.)
<br>
│   ├── css/
<br>
│   │   └── style.css                   # Main stylesheet
<br>
│   ├── js/
<br>
│   │   └── main.js                     # Main JavaScript file
<br>
│   └── images/
<br>
│       └── logo.png                    # Example image file
<br>
│
<br>
├── graphql/                            # Directory for GraphQL schema and resolvers
<br>
│   ├── schema.graphql                  # GraphQL schema definition
<br>
│   └── resolvers/
<br>
│       ├── classroomResolvers.js       # Resolvers for classroom operations
<br>
│       ├── subjectResolvers.js         # Resolvers for subject operations
<br>
│       ├── teacherResolvers.js         # Resolvers for teacher operations
<br>
│       └── allotmentResolvers.js       # Resolvers for allotment operations
<br>
│
<br>
├── public/                             # Public directory accessible by web server
<br>
│   ├── index.html                      # Home page
<br>
│   ├── login.html                      # User login page
<br>
│   ├── dashboard.html                  # Admin dashboard
<br>
│   ├── create_timetable.html           # Timetable creation page
<br>
│   └── view_timetable.html             # View timetable page
<br>
│
<br>
├── src/                                # Source directory for PHP files
<br>
│   ├── addclassroomFormValidation.php  # Form validation for adding classroom
<br>
│   ├── addclassrooms.php               # Add classrooms script
<br>
│   ├── addsubjectFormValidation.php    # Form validation for adding subject
<br>
│   ├── addsubjects.php                 # Add subjects script
<br>
│   ├── addteacherFormValidation.php    # Form validation for adding teacher
<br>
│   ├── addteachers.php                 # Add teachers script
<br>
│   ├── adminFormvalidation.php         # Admin form validation
<br>
│   ├── adminform.php                   # Admin form script
<br>
│   ├── algo.php                        # Algorithm script
<br>
│   ├── allotclasses.php                # Allot classes script
<br>
│   ├── allotmentFormvalidation.php     # Form validation for allotment
<br>
│   ├── allotmentpracticalFormvalidation.php # Practical allotment form validation
<br>
│   ├── allotpracticals.php             # Allot practicals script
<br>
│   ├── allotsubjects.php               # Allot subjects script
<br>
│   ├── assignSubstituteFormValidation.php # Form validation for assigning substitute
<br>
│   ├── connection.php                  # Database connection script
<br>
│   ├── curl.php                        # CURL script
<br>
│   ├── deleteallotment.php             # Delete allotment script
<br>
│   ├── deleteclassroom.php             # Delete classroom script
<br>
│   ├── deletesubject.php               # Delete subject script
<br>
│   ├── deleteteacher.php               # Delete teacher script
<br>
│   ├── facultyformvalidation.php       # Faculty form validation
<br>
│   ├── facultypage.php                 # Faculty page script
<br>
│   ├── func.php                        # General functions script
<br>
│   ├── generatetimetable.php           # Generate timetable script
<br>
│   ├── getcellindex.php                # Get cell index script
<br>
│   ├── send.php                        # Send script (for notifications or similar)
<br>
│   ├── sms.php                         # SMS sending script
<br>
│   ├── studentvalidation.php           # Student validation script
<br>
│   └── index.php                       # Main index file
<br>
│
<br>
├── config.php                          # Database configuration file
<br>
├── timetable.sql                       # SQL file for setting up the database schema
<br>
├── server.js                           # Node.js server file for GraphQL (optional, if using Node.js)
<br>
├── package.json                        # Node.js package file (if using Node.js)
<br>
└── README.md                           # Project README file
<br>

##License
This project is licensed under the MIT License - see the LICENSE file for details.

