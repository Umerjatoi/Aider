# Task Tracker REST API

## Overview

This is a simple REST API for a Task Tracker application built using Flask and SQLite. It supports user registration and login with JWT authentication.

## Features

- **User Registration**: Register a new user with a username, email, and password.
- **User Login**: Authenticate a user and return a JWT token.

## Endpoints

- `POST /api/register`: Register a new user.
- `POST /api/login`: Login a user and receive a JWT token.

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:
   ```bash
   python app.py
   ```

3. Run tests:
   ```bash
   python -m unittest discover tests
   ```

## Configuration

- The application uses SQLite as the database.
- JWT tokens are used for authentication.

## Constraints

- Maximum of 10,000 tasks per user.
- SQLite is the only supported database.
