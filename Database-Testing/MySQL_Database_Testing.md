# Database Testing Using MySQL

This document explains the basic database testing performed using MySQL as part of manual QA testing.

---

## Objective
The objective of database testing was to verify that data entered from the frontend is correctly stored and retrieved from the backend database.

---

## Database Tool Used
- MySQL Workbench

---

## Sample Scenario
User registration and data validation.

---

## Table Structure (Sample)

users table:
- id
- name
- email
- password

---

## SQL Queries Used

### 1. Verify User Data Insertion

Query:
SELECT * FROM users;

Purpose:
To check whether user data is successfully inserted into the database after registration.

---

### 2. Verify Specific User Record

Query:
SELECT * FROM users WHERE email = 'akash@test.com';

Purpose:
To confirm that the correct user record exists in the database.

---

### 3. Check for Duplicate Records

Query:
SELECT COUNT(*) FROM users WHERE email = 'akash@test.com';

Purpose:
To ensure that duplicate user records are not created.

---

## Expected Result
- User data should be present in the database
- Only one record should exist for a unique email

---

## Actual Result
- User record was found successfully
- No duplicate entries observed

---

## Notes
Database validation helped confirm that frontend actions were correctly reflected in the backend database.
This testing was performed using basic SELECT and WHERE queries commonly used in manual QA roles.
