# AuthTest

A simple authentication service built with **Spring Boot**, **PostgreSQL**, and **JWT** for secure user authentication and registration.

## Features

- User registration
- User login
- JWT token generation and validation
- PostgreSQL integration

## Endpoints

### `POST /auth/register`
Registers a new user.

### `POST /auth/login`
Registers a new user.

**Request Body:**
```json
{
  "username": "your_username",
  "password": "your_password"
}
