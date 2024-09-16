# SD-3101 [STUDENT-ATTENDANCE SYSTEM]

![image](https://github.com/user-attachments/assets/2a4f0ef0-737e-443c-93f5-a40932077e2a)


## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Chagelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Introduction
- The Student Attendance System is a PHP-based web application designed to manage student attendance records efficiently. It is developed by Code Camp BD and organized into two main sections: Admin Panel and Teacher Panel.

## Project Overview
- The system enables administrators to manage users, teachers to track attendance for specific subjects, and students to view their attendance records.

## Objectives
- Simplify student attendance tracking
- Provide role-specific dashboards for admins and teachers

## Features
- Admin and Teacher panels
- User creation and data management
- Attendance filtering and reporting

## Technologies Used
- Frontend: HTML, CSS, SCSS, JavaScript (with frameworks like Bootstrap for responsive design)
- Backend: PHP, Node.js
- Database: MySQL
- Version Control: Git for code management

## Setup and Installation

1. **Clone the repository:**

   git clone git https://github.com/dev-mhrony/Student-Attendance-System01.git
   
2. **Set up the environment:**
	- Download and install XAMPP
    - Open the XAMPP and start Apache and MySQL services

3. **Database Setup**:
    - Import the provided database SQL file into phpMyAdmin.
    - Name the databasename attendancemsystem01
    - Open the dbcon.php file in Include and update the database name:
  ```php
   &db = "attendancemsystem01"
   ```
   
4. **Run the project:**
   - Move the project file in htdocs folder in XAMPP directory
   - Access the site by typing http://localhost/attendancemsystem01-website/

 ## Usage Instructions

- **Admin Login Details**
  Email : admin@mail.com
  Password: Password@123

- **Teacher Login Details** 
  Email : teacher@mail.com
  Password: pass123

  ## Project structure
  ```
  ├── STUDENT-ATTENDANCE SYSTEM
  ├── Admin
  │   ├── css
  │   ├── font
  │   ├── img
  │   ├── Includes
  │   ├── js
  │   ├── scss
  │   ├── ajaxClassArms.php
  │   ├── ajaxClassArms2.php
  │   ├── createClass.php
  │   ├── createClassArms.php
  │   ├── createClassTeacher.php
  │   ├── createSessionTerm.php
  │   ├── createStudents.php
  │   ├── createUsers.php
  │   ├── index.php
  │   ├── logout.php
  │   └── Readme.md
  ├── ClassTeacher
  │   ├── css
  │   ├── font
  │   ├── img
  │   ├── Includes
  │   ├── js
  │   ├── scss
  │   ├── ajaxClassArmsallTypes.php
  │   ├── downloadRecord.php
  │   ├── index.php
  │   ├── logout.php
  │   ├── takeAttendance.php
  │   ├── viewAttendance.php
  │   ├── viewStudentAttendance.php
  │   └── viewStudents.php
  ├── css
  │   ├── ruang-admin.css
  │   └── ruang-admin.min.css
  ├── DATABASE FILE
  │   └── attendancemsystem01.sql
  ├── fonts
  │   ├── Nunito-Regular.ttf
  │   └── OFL.txt
  ├── img
  │   ├── logo
  │   └── user-icn.png
  ├── Includes
  │   ├── dbcon.php
  │   └── session.php
  ├── js
  │   ├── demo
  │   ├── ruang-admin.js
  │   └── ruang-admin.min.js
  ├── scripts
  │   └── saveMember.php
  ├── scss
  │   ├── navs
  │   ├── utilities
  │   ├── buttons.scss
  │   ├── cards.scss
  │   ├── charts.scss
  │   ├── dropdown.scss
  │   ├── error.scss
  │   ├── footer.scss
  │   ├── global.scss
  │   ├── login.scss
  │   ├── mixins.scss
  │   ├── navs.scss
  │   ├── utilities.scss
  │   ├── variables.scss
  │   └── sb-admin-2.scss
  ├── vendor
  │   ├── bootstrap
  │   ├── datatables
  │   ├── fontawesome-free
  │   ├── jquery
  │   └── jquery-easing
  ├── classTeacherLogin.php
  ├── forgotPassword.php
  ├── index.php
  └── README.md

## Contributors

- **John Henry Barba**: Lead Developer, Backend Developer
- **Raven Ashley Reyes**: Frontend Developer, UI/UX Designer
- **Gerald Villaran**: Project Manager, Tester

## Project Timeline

- **Week 1-2**: Research and project planning.
- **Week 3-5**: Design and setup.
- **Week 6-10**: Implementation.
- **Week 11-12**: Testing and debugging.
- **Week 13-14**: Final presentation and documentation.

## Changelog

### [Version 1.0.0] - 2024-09-07
- Initial release of the project.
- Added basic functionality for [Feature 1], [Feature 2], and [Feature 3].

### [Version 1.1.0] - 2024-09-14
- Improved user interface for [Feature 1].
- Fixed bugs related to [Feature 2].
- Updated project documentation with setup instructions.

### [Version 1.2.0] - 2024-09-21
- Added new functionality for [Feature 4].
- Refactored codebase for better performance.
- Added unit tests for [Feature 3] and [Feature 4].

## Acknowledgments

Acknowledge any resources, mentors, or external tools that helped in completing the project.

This project was built from [Original Project Name](https://github.com/dev-mhrony/Student-Attendance-System01), created by [dev-mhrony]. You can view the original repository [here](https://github.com/dev-mhrony/Student-Attendance-System01).

## License

Specify the project's license. For starters, adapt the license of the original repository.
"# student-attendance-management-system" 
