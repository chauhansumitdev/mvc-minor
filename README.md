# MVC Design Implementation

## Overview
This project is an implementation of the Model-View-Controller (MVC) design pattern. It demonstrates how to build a structured and maintainable application architecture. The project includes a single API endpoint for user registration.

## API Specification

### User Registration

#### Endpoint
`POST /user`

#### Request
- **Headers:**
  - `Content-Type: application/json`
- **Body:**
  ```json
  {
    "username": "your-username",
    "password": "your-password"
  }
  ```

## Example

### Request
```sh
curl -X POST http://localhost:8080/user \
-H "Content-Type: application/json" \
-d '{"username": "testUser", "password": "testPass"}'
```
