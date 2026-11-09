# SQL Server Database Activity Monitoring, Backup and Restore Management System

A SQL Server database monitoring and management solution developed to improve database activity visibility, security monitoring, backup management, and recovery readiness.

## Project Overview

The **SQL Server Database Activity Monitoring, Backup and Restore Management System** is a technical project developed during industrial training at the Central Engineering Consultancy Bureau (CECB).

The project focuses on monitoring SQL Server database activities, maintaining user activity records, collecting database error information, tracking restore operations, and supporting automated database backup management.

The solution was developed and tested in a controlled local SQL Server environment. Production deployment at CECB is a proposed future activity, subject to technical evaluation and management approval.

## Objectives

- Monitor SQL Server database activities.
- Record successful and failed login activities.
- Track user roles and database operations.
- Collect and maintain database error records.
- Monitor database restore history.
- Automate database backup operations.
- Support backup synchronization to OneDrive.
- Provide information for database activity reporting.
- Improve database security monitoring and recovery readiness.

## Key Features

### 1. Database Activity Monitoring
- SQL Server Audit integration.
- Login and logout activity monitoring.
- Database operations monitoring.
- User and role identification.
- Activity timestamps and related information.

### 2. User Role Monitoring
- User role mapping.
- Monitoring activities based on database users and roles.
- Recording user-related database operations.

### 3. Database Error Monitoring
- Collection of SQL Server error information.
- Recording error numbers, severity, and related details.
- Maintaining error records for review.

### 4. Backup Management
- Automated SQL Server database backups.
- Backup file organization.
- Backup history verification.
- Support for backup synchronization with OneDrive.

### 5. Restore History Management
- Collection of database restore history.
- Recording restore dates and database details.
- Tracking restore status and related information.

### 6. Automated Data Collection
- Windows Task Scheduler integration.
- Batch scripting for automated execution.
- PowerShell support for system administration.
- Configured activity collection interval: Every 5 minutes.

## Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft SQL Server 2022 | Database platform |
| SQL Server Management Studio (SSMS) | Database administration |
| T-SQL | Database scripts and stored procedures |
| SQL Server Audit | Activity monitoring |
| Windows Task Scheduler | Scheduled automation |
| Batch Scripting | Automated script execution |
| PowerShell | Windows administration |
| Microsoft OneDrive | Backup synchronization |

## System Environment

- Operating System: Windows 10 Pro
- Database Server: Microsoft SQL Server 2022 Express Edition
- Database Administration Tool: SQL Server Management Studio
- Development Environment: Local test environment

## Project Structure

This repository contains the SQL scripts, configuration files, automation scripts, documentation, and supporting components required for the monitoring and backup management solution.

Refer to the individual folder README files for component-specific information, configuration requirements, and execution instructions.

## Installation and Configuration

1. Review the project documentation and folder README files.
2. Verify the SQL Server version and environment requirements.
3. Review all SQL scripts before execution.
4. Configure the required database objects and SQL Server Audit components.
5. Configure the required folder paths and permissions.
6. Configure Windows Task Scheduler for automated collection.
7. Configure backup destinations and synchronization settings.
8. Execute the verification scripts to check the system configuration.

**Important:** Follow the detailed deployment instructions provided in the project documentation. Do not execute scripts against a production database without proper review and authorization.

## Security and Deployment Notice

This project was developed and tested using a local/test SQL Server environment.

It has not been confirmed as deployed to the original CECB production database.

Any future production deployment must be reviewed and approved by the relevant CECB technical and management teams.

Before deployment, verify:

- Database permissions and user roles.
- SQL Server Audit configuration.
- Backup storage locations and access permissions.
- Scheduled task execution permissions.
- Backup integrity and restore procedures.
- Security and confidentiality requirements.

## Project Status

**Development and Local Testing:** Completed components are subject to final verification.

**Production Deployment:** Proposed future implementation, subject to approval.

## Learning Outcomes

Through this project, practical experience was gained in:

- SQL Server database administration.
- Database security and auditing.
- User and role management.
- T-SQL scripting and stored procedures.
- Automated backup and restore management.
- Windows Task Scheduler.
- PowerShell and batch scripting.
- Database monitoring and verification.

## Acknowledgement

Developed as part of the industrial training programme at the **Central Engineering Consultancy Bureau (CECB)** while following the Bachelor of Information and Communication Technology (Honours) programme at the University of Vavuniya.

---

**Project:** SQL Server Database Activity Monitoring, Backup and Restore Management System

**Repository:** [GitHub Repository](https://github.com/DulanMadhukaWeerathunga2000/CECB-SQL-Server-Database-Monitoring)
