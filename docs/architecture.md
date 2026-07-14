# Credit Card Fraud Detection System Architecture

## Overview

The Credit Card Fraud Detection System is a secure web application that monitors financial transactions and identifies suspicious activities using configurable fraud detection rules. The platform supports Administrators, Analysts, and Viewers through a role-based architecture.

---

## Architecture

### Presentation Layer

- HTML5
- CSS3
- Tailwind CSS
- JavaScript

Provides responsive dashboards, transaction management, fraud alerts, analytics, and reporting interfaces.

---

### Application Layer

Built with PHP and responsible for:

- Authentication
- Authorization
- Transaction Management
- Fraud Detection
- Alert Management
- Report Generation
- Audit Logging

---

### Fraud Detection Engine

Implements configurable rule-based detection including:

- Amount Threshold Rule
- Transaction Frequency Rule
- Location Anomaly Rule
- Failed Authentication Rule

---

### Database Layer

MySQL stores:

- Users
- Transactions
- Fraud Alerts
- Fraud Rules
- Audit Logs
- Reports
- Login Attempts

---

## Core Modules

### Authentication Module

- Login
- Registration
- Password Reset
- Session Management

### Transaction Module

- Transaction Processing
- Search
- Filtering
- Import

### Fraud Engine

- Rule Evaluation
- Risk Classification
- Alert Generation

### Alert Module

- Alert Assignment
- Investigation
- Resolution
- False Positive Management

### Administration Module

- User Management
- Rule Configuration
- Reports
- Audit Logs

---

## Security Features

- Role-Based Access Control
- Password Hashing
- Session Security
- CSRF Protection
- SQL Injection Prevention
- XSS Protection
- AES-256 Encryption
- Rate Limiting
- Audit Logging

---

## Technologies

- PHP 8.2+
- MySQL 8+
- JavaScript
- Tailwind CSS
- Chart.js
- Composer

---

## Deployment

Compatible with:

- Apache
- XAMPP
- WAMP
- LAMP
- Shared PHP Hosting
