# E-Shala – Online Learning Management System

E-Shala is a web-based Learning Management System (LMS) developed to make online education more accessible and interactive. The platform connects students and tutors, allowing tutors to create and manage courses while students can access learning materials, watch educational videos, participate in quizzes, and track their learning activities.

## Features

### Student Module
- Student Registration and Login
- Browse and Explore Available Courses
- Access Video-Based Learning Content
- View Course Playlists and Study Materials
- Download Notes and Learning Resources
- Participate in Interactive Quizzes
- Bookmark Courses and Playlists
- Like and Comment on Learning Content
- Search for Courses and Tutors
- Manage Student Profiles

### Tutor / Admin Module
- Dedicated Tutor Dashboard
- Tutor Registration and Authentication
- Create, Update, and Manage Courses
- Upload Educational Videos and Content
- Organize Courses into Playlists
- Upload Notes and Study Materials
- Create and Manage Quizzes
- Add Questions and Multiple-Choice Answers
- Manage Student Comments and Engagement
- Monitor Course Content and Activity

## Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Database Connectivity:** PHP PDO

## Project Structure

- `admin/` – Tutor dashboard and course management
- `components/` – Database connection and reusable components
- `css/` – Website styling
- `js/` – JavaScript functionality
- `images/` – Project images and assets
- `uploaded_files/` – Uploaded educational content and resources
- `course_db.sql` – MySQL database structure

## Installation and Setup

1. Install XAMPP or another PHP and MySQL development environment.
2. Clone or download this repository.
3. Copy the project folder into the XAMPP `htdocs` directory.
4. Start Apache and MySQL from XAMPP Control Panel.
5. Open phpMyAdmin.
6. Create a database named `course_db`.
7. Import the `course_db.sql` file into the database.
8. Configure the database connection in `components/connect.php` if required.
9. Open the following URL in your browser:

   `http://localhost/E-Shala/`

## Project Objective

The main objective of E-Shala is to provide a centralized digital learning environment where students can access educational resources and tutors can efficiently manage and publish learning content.

## Developer

**Pratik Ghorpade**

Computer Science and Engineering


