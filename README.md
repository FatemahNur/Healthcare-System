# Healthcare-System
# SE3350 Group Project - Vision Health Management System

This project is a full-stack web application developed as part of the SE3350 course. It provides a role-based platform for managing patient appointments, health records, and diagnostic results with separate interfaces for Admins, Doctors, and Patients.

## Project Structure

# ├── backend/
# Node.js/Express RESTful API │ ├── src/ │ │ ├── config/ 
# Database config and connection │ │ ├── controllers/ 
# Logic for handling API requests │ │ ├── middlewares/ 
# Authentication & other middleware │ │ ├── models/ 
# Mongoose models (User, Diagnosis, Exams, etc.) │ │ ├── routes/ 
# API route definitions per user type │ │ ├── app.js 
# Express app configuration │ │ └── server.js 
# Server startup │ └── package.json # Backend dependencies ├── frontend/ # React-based client-side application │ └── ... 
# Components, pages, assets (details TBD)


## User Roles

- **Admin**: Manages users and appointments.
- **Doctor**: Views assigned patients, reviews medical tests and diagnoses.
- **Patient**: Books appointments, fills questionnaires, and views exam results.

## Getting Started

### Backend Setup
## pgAdmin - Postgresql running locally or provide a connection string via environment variables
## Technologies Used
Frontend: React, HTML/CSS, Axios

Backend: Node.js, Express.js, Postgresql

Auth: JWT (JSON Web Token)

Tools: Git, Postman (for API testing)

## Features
User authentication and role-based authorization

Appointment booking and status management

Patient questionnaire submission

Vision test and diagnosis recording

Admin dashboard for user control


```bash
cd backend
npm install
npm start

cd frontend
npm install
npm start




