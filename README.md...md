# Cybersecurity Internship Project

Name : Eman Aftab

## Project Overview
This project was completed as part of the DevelopersHub Cybersecurity Internship. The objective was to analyze a web 
application, identify security vulnerabilities, implement security measures, and improve the application's 
overall security.

## Technologies Used

- Node.js
- bcrypt
- validator
- jsonwebtoken (JWT)
- Helmet.js
- Winston
- Nmap
- OWASP ZAP

# Week 1 - Security Assessment

## Tasks Performed

- Set up the web application.
- Explored Signup and login.
- Tested for SQL Injection.
- Reviewed password storage.
- Identified security misconfigurations.

----

# Week 2 - Security Implementation

## Security Improvements

Input Validation:

- Implemented input validation using Validator.

Password Security:

- Implemented password hashing using bcrypt.

Authentication:

- Added JWT-based authentication.

HTTP Security:

- Implemented Helmet.js for secure HTTP headers.

----

# Week 3 - Advanced Security

## Penetration Testing

- Performed basic security testing using Nmap.
- Tested application security after fixes.

## Logging

- Implemented Winston logging.
- Generated security.log for monitoring.

## Security Checklist

- Input Validation
- Password Hashing
- JWT Authentication
- Secure HTTP Headers
- Logging
- Basic Penetration Testing

---

# Project Structure

```
Project
│
├── routes
├── models
├── middleware
├── logs
│   └── security.log
├── screenshots
├── reports
├── server.js
├── package.json
├── README.md

# Testing Tools

- OWASP ZAP
- Browser Developer Tools
- Nmap

# Results

- SQL Injection protection.
- Passwords securely hashed.
- JWT authentication added.
- Secure HTTP headers enabled.
- Application logging implemented.
- Overall application security significantly improved.


----

# Week 4 - Advanced Threat Detection & Web Security

## Goal
Implement advanced security measures, detect threats in real-time, and secure API endpoints.

## Intrusion Detection & Monitoring
- Configured Fail2Ban for real-time monitoring.
- Monitored and logged multiple failed login attempts.

## API Security Hardening
- Implemented rate limiting using **express-rate-limit**.
- Configured **CORS** to restrict unauthorized access.
- Protected API endpoints using authentication (JWT/API security).

## Security Headers & HTTPS
- Implemented **Content Security Policy (CSP)**.
- Enabled **Strict-Transport-Security (HSTS)** headers.

## Deliverables
- Secured API with rate limiting and authentication.
- Security headers (CSP and HSTS) configured.
- Fail2Ban monitoring implemented.
- Updated project documentation.

## Testing
- Verified rate limiting.
- Verified CORS restrictions.
- Tested CSP and HSTS headers.
- Confirmed failed login monitoring.
