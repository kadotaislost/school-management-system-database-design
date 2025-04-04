# School Management System

A comprehensive system for managing school operations, including user management, student records, staff management, academics, attendance, examinations, and fee tracking.

## Table of Contents

1. [Requirements](#requirements)
   - [User Management](#user-management)
   - [Student Management](#student-management)
   - [Staff Management](#staff-management)
   - [Academic Structure](#academic-structure)
   - [Attendance Tracking](#attendance-tracking)
   - [Examination & Grading](#examination--grading)
   - [Fee Management](#fee-management)
   - [Reporting & Analytics](#reporting--analytics)
   - [Notifications & Alerts](#notifications--alerts)
2. [Features List](#features-list)
3. [ERD](#erd)

## Requirements

### User Management

#### 1.1 Authentication & Authorization

- Users can log in with username/email and password
- Passwords are securely hashed
- Role-based access control (admin, principal, teacher, student, staff, guardian)
- Admins can create, update, and deactivate user accounts

#### 1.2 Profile Management

- Users can view personal details (name, email, phone, address)
- Students and staff can view assigned roles and permissions

### Student Management

#### 2.1 Student Registration & Enrollment

- Admins can register new students with personal details
- Students assigned to classes with unique roll numbers
- Enrollment date and academic year recorded

#### 2.2 Student Records & Updates

- Admin can update student details (address, contact info, DOB)
- Students can be promoted to next grade level
- Search/filter students by name, class, or academic year

#### 2.3 Guardian/Parent Management

- Guardians assigned to students with relationship type
- Multiple guardians per student with primary designation
- Guardians can view linked student's attendance, grades, and fees

### Staff Management

#### 3.1 Staff Registration & Roles

- Admins can add staff members with positions
- Staff details (hire date, contact info) can be updated
- Teachers can be assigned subjects they teach

#### 3.2 Teacher-Subject Assignment

- Teachers assigned to one or more subjects
- Teachers can view assigned classes and subjects

### Academic Structure

#### 4.1 Class & Subject Management

- Admins can create classes (grade level + section)
- Subjects can be added with unique codes
- Subjects assigned to classes

#### 4.2 Timetable Scheduling

- Weekly timetable creation for each class
- Entries include subject, teacher, day, and time slot
- No overlapping classes for same teacher/class

### Attendance Tracking

#### 5.1 Daily Attendance

- Teachers can mark attendance (Present/Absent/Late)
- Records stored by date and class
- Students/guardians can view attendance history

#### 5.2 Attendance Reports

- Generate reports by student, class, or date range
- Identify trends (frequent absences, late arrivals)

### Examination & Grading

#### 6.1 Exam Scheduling

- Admins can create exams with start/end dates
- Exams linked to academic year

#### 6.2 Marks Entry & Grading

- Teachers can enter marks (0-100) per subject
- Marks can be updated before finalizing
- Students/guardians can view grades

#### 6.3 Grade Reports

- Generate report cards
- Calculate overall performance (pass/fail, averages)

### Fee Management

#### 7.1 Fee Assignment & Tracking

- Admins can assign fees with due dates
- Payment status tracking (Paid/Unpaid/Overdue)
- Payment date recording

#### 7.2 Fee Reports & Notifications

- Generate payment reports by student/status
- Send reminders for overdue fees

### Reporting & Analytics

#### 8.1 Student Performance Reports

- View grades, attendance trends
- Compare performance across exams

#### 8.2 Staff & Class Reports

- List of teachers and assigned subjects
- Class-wise student lists with attendance

#### 8.3 Financial Reports

- Total fees collected vs pending
- Overdue fee summaries

### Notifications & Alerts

- Guardians receive absence alerts
- Teachers notified of timetable changes
- Fee payment reminders sent

## Features List

### User Management

- User registration with roles (admin, principal, teacher, student, staff)
- Authentication and login tracking
- Role-based access control
- Profile management

### Student Management

- Student registration and profile management
- Enrollment tracking
- Demographic information storage
- Class assignment with roll numbers
- Guardian/parent associations

### Staff Management

- Staff registration and profile management
- Position tracking
- Hiring date records
- Contact information storage

### Academic Structure

- Class creation (grade levels 1-12 + sections)
- Subject management with unique codes
- Class-subject mapping
- Teacher-subject assignments
- Academic year tracking

### Attendance System

- Daily attendance recording (present, absent, late)
- Class-based tracking
- Date-specific records

### Examination & Grading

- Exam scheduling with date ranges
- Subject-wise grade recording
- Marks entry (0-100)
- Performance remarks
- Academic year exam tracking

### Timetable Management

- Class-wise timetable creation
- Subject scheduling by weekday
- Time slot management
- Teacher assignment

### Financial Management

- Student fee tracking
- Payment status monitoring
- Due date tracking
- Payment recording

### Guardian/Parent Management

- Guardian registration
- Student-guardian relationship tracking
- Contact information storage
- Multiple guardians per student

## ERD

![ERD](image-url "school_management_ERD.png")
