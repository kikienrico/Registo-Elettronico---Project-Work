# 🏫 School Management System

A comprehensive digital school registry system to manage students, teachers, classes, and grades.


## 📋 Project Overview

The School Management System is a web-based application designed to digitize school management processes. The platform offers different access levels and features based on user roles, facilitating efficient administration of educational data.

### ✨ Key Features

- **Multi-role Access System**: Different interfaces for students, teachers, editors, and administrators
- **Grade Management**: Record and review academic performance
- **User Management**: Create and manage user accounts
- **Class & Schedule Management**: Organize courses and timetables
- **Responsive Design**: Works across desktop and mobile devices

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## 🏗️ Project Structure

```
school-management-system/
├── admin_dashboard.php       # Administrator control panel
├── authenticate.php          # User authentication logic
├── classi.php                # Class management
├── config.php                # Configuration settings
├── create_user.php           # User creation interface
├── index.php                 # Main entry point
├── logout.php                # Logout functionality
├── materie.php               # Subjects management
├── modifica_orario.php       # Schedule editing
├── orario.php                # General schedule view
├── orario_studente.php       # Student-specific schedule
├── student_dashboard.php     # Student interface
├── teacher_dashboard.php     # Teacher interface
├── /Documentazione/          # Project documentation
│   └── Documentazione.pdf    # Detailed project docs
└── /uploads/                 # Image assets
    ├── default.png           # Default display image
    ├── back.png              # Background image
    ├── back_white.png        # Alternative background
    ├── students.png          # Student-related imagery
    └── teacher.png           # Teacher-related imagery
```

## 📅 Development Timeline

The project was developed from March 3, 2025, to April 11, 2025, following a structured development plan:

| Phase | Dates | Description |
|-------|-------|-------------|
| Project Initialization | Mar 3, 2025 | Official project kickoff |
| Requirements Analysis | Mar 4-7, 2025 | Defining system requirements |
| UI Design | Mar 8-13, 2025 | Creating user interface designs |
| Backend Development | Mar 18-27, 2025 | Building system logic and authentication |
| Frontend Development | Mar 28-Apr 3, 2025 | Implementing user interfaces |
| Database Design | Apr 4-5, 2025 | Creating database schemas |
| Testing & Debugging | Apr 7-9, 2025 | Quality assurance |
| Final Deployment | Apr 10-11, 2025 | System launch |

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/school-management-system.git
   ```

2. Set up your web server (Apache/Nginx) to point to the project directory

3. Import the database schema (found in documentation)

4. Configure database connection in `config.php`:
   ```php
   // Example configuration
   $db_host = 'localhost';
   $db_user = 'root';
   $db_pass = 'your_password';
   $db_name = 'school_management';
   ```

5. Access the system through your web browser

## 👥 User Roles

The system supports four distinct user roles:

1. **Student**: View personal grades, schedules, and class information
2. **Teacher**: Enter and manage grades, view class information
3. **Editor**: Create and manage user accounts (no access to grades)
4. **Administrator**: Full system access with all privileges

## 🔗 Additional Resources

- [Documentazione](/Documentazione/Documentazione.pdf)
- [UI Mockups](https://www.canva.com/design/DAGgqqg0AWA/NV8wCs5jJUJIQHGaFym1QA/edit)
- [Gantt Chart](https://www.canva.com/design/DAGnOS1JAuk/zpuYIicTpy5MBzgPF3c5Lg/edit)
- [ER Schema](https://www.canva.com/design/DAGnOalb4ds/soVqHlr9hU_SLHwlTylGZQ/edit)

## 📊 Database Schema

The system uses a relational database with the following key tables:
- `Utenti` (Users)
- `Studenti` (Students)
- `Docenti` (Teachers)
- `Classi` (Classes)
- `Materie` (Subjects)
- `Voti` (Grades)
- `Credenziali_Temporanee` (Temporary Credentials)

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

© 2025 School Management System | Developed with ❤️ for educational institutions
