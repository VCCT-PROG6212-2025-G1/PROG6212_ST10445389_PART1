CMCS - Contract Monthly Claim System
A web-based platform for managing monthly claims in academic institutions.
Student: Kallan Jones (ST10445389) | Course: PROG6212 Programming 2B
Overview
CMCS streamlines the claim submission and approval process for three user types:

Lecturers: Submit and track monthly claims
Programme Coordinators: Review and approve lecturer claims
Academic Managers: Provide final approval for claims

Key Features

Role-based dashboards with relevant metrics
Automated claim calculations (hours × hourly rate)
Document upload support (PDF, Word, Excel)
Real-time claim status tracking
Complete claim history and audit trail

Technology Stack

Backend: ASP.NET Core MVC
Database: SQL Server with Entity Framework
Frontend: Bootstrap for responsive design
Authentication: Role-based access control

Workflow

Lecturer submits claim with supporting documents
Programme Coordinator reviews and approves/rejects
Academic Manager provides final approval
Claim is processed and recorded

System Constraints

Maximum 100 concurrent users
10MB file upload limit
PDF, Word, Excel files only
Windows Server hosting required

Installation

Clone repository
Configure SQL Server connection
Run Entity Framework migrations
Deploy to Windows Server

Academic Integrity
This project used Claude.ai for documentation guidance while maintaining academic standards.
