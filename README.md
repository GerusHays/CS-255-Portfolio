# CS-255-Portfolio
# DriverPass System Design

## Overview
This repository contains the Business Requirements and System Design documents for the DriverPass system. The purpose of this project was to analyze a client’s needs and design a cloud-hosted web application that supports driver training operations. DriverPass wanted a centralized system that allows students to prepare for DMV tests through online practice exams while also scheduling in-person driving lessons. The system also needed to allow staff and administrators to manage customers, training packages, scheduling, and reporting.

This project demonstrates my ability to gather requirements, interpret business needs, and translate those needs into a structured system design using UML and technical architecture planning.

---

## Client and Problem
**Client:** DriverPass (driver training company)

**Problem they wanted to solve:**
Many students fail DMV driving exams due to lack of preparation, outdated study material, and difficulty scheduling lessons.

**Solution they needed:**
A web-based system that allows:

- Customers to register and manage accounts  
- Schedule, modify, and cancel driving lessons  
- Take online practice tests and track progress  
- Purchase and manage training packages  
- Staff to manage scheduling and customer accounts  
- Administrators to manage system settings and generate reports  

---

## System Design Summary
The system was designed as a **cloud-hosted web application** with the following core components:

**Frontend**
- Browser-based interface (desktop and mobile)
- Customer dashboard for scheduling and test tracking
- Staff/admin interface for managing customers and appointments

**Backend**
- Application server handling scheduling logic and user management
- Secure authentication system with password reset functionality
- Role-based access control (RBAC)

**Database**
- Stores:
  - Customer accounts
  - Lesson reservations
  - Training packages
  - Practice test results
  - Instructor notes

**Infrastructure**
- Cloud hosting environment
- HTTPS encryption
- Backup and recovery handled by hosting provider
- Scalable to support multiple concurrent users

---

## UML and Design Artifacts
This project includes multiple UML diagrams to model the system:

- Use Case Diagram – shows how users interact with the system
- Activity Diagrams – shows workflows like scheduling lessons and taking practice tests
- Sequence Diagram – shows interaction between system components
- Class Diagram – shows system data structure and relationships

These diagrams helped translate business requirements into a technical system design.

---

## What I Did Well
- Clearly identified both **functional and nonfunctional requirements**
- Designed the system with **security, scalability, and cloud deployment in mind**
- Defined multiple **user roles and permission levels**
- Used UML diagrams to model workflows and system structure
- Connected business needs to technical architecture decisions

---

## What I Would Improve
If I continued this project further, I would:

- Define a detailed **database schema**
- Specify exact **technologies** (ex: AWS, PostgreSQL, React, Node.js)
- Design detailed **API endpoints**
- Include more **error handling and edge case scenarios**
- Create a deployment architecture diagram

This would move the project closer to full implementation.

---

## How I Approach Software Design
My general system design process is:

1. Understand the business problem
2. Identify users and system requirements
3. Define functional and nonfunctional requirements
4. Model workflows using UML diagrams
5. Design system architecture and infrastructure
6. Ensure security, scalability, and maintainability

This structured approach helps ensure the system meets both technical and business goals.

---

## Skills Demonstrated
- System analysis and requirements gathering  
- UML modeling and system visualization  
- Cloud-based system architecture design  
- Security and access control planning  
- Technical documentation  

---

## Repository Contents
Business-Requirements-Document.docx
System-Design-Document.docx
README.md

---

## Portfolio Purpose
This artifact demonstrates my ability to analyze client requirements and design a complete software system. These are core skills required for software engineering, systems engineering, and technical design roles.
