# Placement Management System

Our system aims to simplify the placement process for College Students, Companies visiting the campus for recruitment, and the College TPO (Training and Placement Officer).

## User Roles:

There are three types of users in the system:

- TPO (Training and Placement Officer)
- Student
- Company (HR)

## Features

### TPO Features:

- View Details: Allows TPO to view personal and college details.
- Update Details: Enables TPO to update all details.
- Change Password: Allows TPO to change their password.
- Add Student: Allows TPO to add students to the database via an Excel file.
- View Student Details: Enables TPO to search and view student information.
- View Company Details: Enables TPO to search and view company details.
- Request Section: Enables TPO to view job requests from companies and assign jobs to students.
- On-campus Job Announcements: Allows TPO to manage on-campus job postings and view applied students.

### Student Features:

- View Details: Enables students to view personal details.
- Update Details: Allows students to update their details.
- Change Password: Enables students to change their password.
- View Company Details: Enables students to search and view company details.
- View Off-campus Jobs: Allows students to browse and apply for jobs posted by companies.
- View Applied Off-campus Jobs: Shows a list of jobs the student has applied for.
- View TPO Details: Allows students to see their assigned TPO's details (if verified).
- View On-campus Jobs: Enables students to view and apply for on-campus jobs assigned by the TPO.
- View Applied On-campus Jobs: Lists on-campus jobs the student has applied for.

### Company (HR) Features:

- View Details: Enables HR to view personal details.
- Update Details: Allows HR to update their details.
- Change Password: Enables HR to change their password.
- View Student Details: Allows HR to search and view student details.
- Job Announcements: Enables HR to announce off-campus jobs for students.
- List of Off-campus Jobs: Allows HR to manage job postings and view applicants.
- View TPO Details: Enables HR to search and view details of TPOs and colleges.
- Request TPO: Allows HR to request TPOs to announce jobs.
- View Requests: Enables HR to update and delete job requests.
- View Accepted Requests: Allows HR to see accepted job requests and view applicants.

## Installation Guide

### Prerequisites

Ensure you have the following installed on your system:

- Node.js
- MySQL
- XAMPP (For managing MySQL and phpMyAdmin)

### Clone the Repository

```
git clone https://github.com/Sahil-4555/Placement_Managment_System.git
```

### Install Dependencies

```
npm i
```

### Configure the Database

1. start `XAMPP (or MySQL service)` and open `phpMyAdmin (http://localhost/phpmyadmin/)`.
2. Create a new database:

```
CREATE DATABASE placement;
```

3. Import the provided SQL file into `phpMyAdmin`.

- Go to Import
- Select the `database/placement.sql` file from the project folder
- Click Go

4. Set Up Variables in `database.js`. Modify values as needed.
5. Start the Server

```
npm start
```

6. If everything is set up correctly, the application will run on:

```
http://localhost:8000
```
