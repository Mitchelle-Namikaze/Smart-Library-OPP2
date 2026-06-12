# Smart Library Management System

## Overview

The Smart Library Management System is a full-stack web application developed using FastAPI, PostgreSQL, SQLAlchemy, and React. The system helps libraries manage books, users, borrowing activities, reservations, and overdue records through a modern role-based platform.

## Features

### Authentication

* User Login
* Role-Based Access Control
* Session Persistence

### User Management

* Register Users
* Assign Roles (Admin, Librarian, Student)
* View User Records

### Book Management

* Add Books
* Edit Books
* Delete Books
* Search Books
* Availability Tracking

### Borrowing System

* Borrow Books
* Return Books
* Due Date Tracking
* Overdue Monitoring

### Reservation System

* Create Reservations
* Approve Reservations
* Reject Reservations
* Automatic Borrow Record Creation After Approval

### Dashboard

* Total Books
* Available Books
* Borrowed Books
* Total Users
* Reservation Statistics

## Technologies Used

### Backend

* FastAPI
* Python
* SQLAlchemy
* PostgreSQL

### Frontend

* React
* Axios
* CSS

### Documentation

* Swagger UI
* ReDoc

## Project Structure

backend/
├── models/
├── routes/
├── schemas/
├── database.py
├── main.py

frontend/
├── src/
│ ├── pages/
│ ├── App.jsx
│ ├── App.css
│ └── main.jsx

## Installation

### Backend

1. Create virtual environment

python -m venv venv

2. Activate virtual environment

Windows:

venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Run backend

uvicorn main:app --reload

### Frontend

1. Install dependencies

npm install

2. Run frontend

npm run dev

## API Documentation

Swagger UI:

http://127.0.0.1:8000/docs

ReDoc:

http://127.0.0.1:8000/redoc

## Author

Mitchelle Kamanda
Group 1

## Academic Project

Object Oriented Programming II

Smart Library Management System
