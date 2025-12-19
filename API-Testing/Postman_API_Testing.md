# API Testing Using Postman

This document describes the basic API testing performed using Postman as part of the QA testing process.

---

## Objective
The goal of this testing was to validate API responses, status codes, and basic request handling without relying on the UI.

---

## API Used for Testing
Base URL:
https://jsonplaceholder.typicode.com

This is a public demo API commonly used for testing and learning purposes.

---

## GET Request Testing

Endpoint:
GET /users

Steps:
1. Open Postman
2. Select GET method
3. Enter the URL https://jsonplaceholder.typicode.com/users
4. Click on Send

Expected Result:
- Status code should be 200 (OK)
- Response body should return a list of users in JSON format

Actual Result:
- Status code 200 received
- User data returned successfully in JSON format

---

## POST Request Testing

Endpoint:
POST /users

Request Body (JSON):
{
  "name": "Akash",
  "email": "akash@test.com",
  "username": "akash123"
}

Steps:
1. Select POST method in Postman
2. Enter the endpoint URL
3. Add request body in JSON format
4. Click on Send

Expected Result:
- Status code should be 201 (Created)
- Response should contain submitted data

Actual Result:
- Status code 201 received
- API accepted the request and returned response successfully

---

## Status Codes Verified
- 200 – Successful request
- 201 – Resource created
- 400 – Bad request (invalid input)
- 404 – Endpoint not found
- 500 – Server error

---

## Notes
This testing was performed to understand backend validation, response handling, and basic API behavior from a QA perspective.
