# hospital-management-system
HMS+ (PHP + MySQL on XAMPP) — Plain-text passwords for older PHP

Quick Start
1) Start XAMPP (Apache + MySQL).
2) Open phpMyAdmin → create database: hms
3) Import db.sql into hms.
4) Copy this folder to C:\xampp\htdocs\hms_plus  (or rename to hms)
5) Visit http://localhost/hms_plus/login.php

Demo logins
- admin / admin123
- recep / recep123
- doc / doc123

Features
- Login with roles (plain-text passwords for compatibility)
- Dashboard with counts + today's appointments
- Patients: add, edit, delete, search by name/phone
- Doctors: add, edit, delete, filter by specialty
- Appointments: create, edit (reschedule/notes/status), delete, filter by date & status
- Users (Admin): add/delete users with roles

Notes
- This is for learning/demo. For production, upgrade to PHP 7.4+ or 8.x and switch to password_hash()/password_verify() + CSRF and validation.
