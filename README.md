# 🎓 Azam Scholarship Management System

A comprehensive, role-based Scholarship Management Platform built with PHP and MySQL. This system bridges the gap between scholarship providers, students, and administrators by offering a centralized, secure, and intuitive digital ecosystem for managing educational funding.

---

## 👥 Core Contributors

**Developed By:**
- **Muzaffar Hussain** (Backend Architecture & Database Design)
- **Sayyed Gufran** (Frontend Integration, Core Logic & System Architecture)

---

## 🚀 Project Overview

The Azam Scholarship Management System is designed to eliminate the manual overhead of traditional scholarship distribution. It features three distinct role-based dashboards to handle the entire lifecycle of a scholarship application—from creation by a provider to application by a student, and final oversight by system administrators.

### 🔑 Key Features

#### 1. Student Portal (`student_dashboard.php`)
- **Profile Management**: Secure registration and profile creation.
- **Scholarship Discovery**: Browse available scholarships filtered by criteria.
- **Application Tracking**: Submit applications and track their real-time status (Pending, Approved, Rejected).

#### 2. Provider Dashboard (`provider_dashboard.php` & `create_scholarship.php`)
- **Fund Management**: Organizations and philanthropists can create and manage new scholarship programs.
- **Application Review**: Review incoming student applications, download documents, and approve or reject candidates.

#### 3. Admin Control Center (`admin_dashboard.php`)
- **User Management**: Oversee all registered students and providers (`admin_manage_users.php`).
- **System Reports**: Generate analytics and audit logs of all scholarship activities and fund distributions (`admin_system_reports.php`).
- **Security**: Centralized control over the platform's integrity.

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Responsive UI)
- **Backend**: PHP (Core PHP / Procedural & OOP logic)
- **Database**: MySQL (`database.sql` includes schema for users, scholarships, and applications)
- **Authentication**: Secure session-based login and password hashing (`login.php`, `register.php`)

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/iInfynite/azamscholarship.git
   ```
2. **Server Environment:** 
   Place the project folder in your local web server's root directory (e.g., `htdocs` for XAMPP or `www` for WAMP).
3. **Database Setup:**
   - Open phpMyAdmin.
   - Create a new database named `azamscholarship`.
   - Import the `database.sql` file provided in the repository to generate the required tables.
4. **Configuration:**
   Update the database connection strings in the PHP files to match your local database credentials (default: root/no password).
5. **Run the Application:**
   Navigate to `http://localhost/azamscholarship/index.php` in your browser.

---

## 📈 Future Scope

- Integration with Email APIs (e.g., SendGrid) for automated application status notifications.
- Advanced AI-based matching algorithm to recommend scholarships to students based on their profile.
- Implementation of a secure payment gateway API for direct fund disbursement.

---

> *This project demonstrates proficiency in full-stack web development, relational database design, role-based access control (RBAC), and building scalable PHP applications.*
