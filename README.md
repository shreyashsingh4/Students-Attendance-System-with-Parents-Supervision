# Student's Attendance System with Parent's Supervision

## Overview
Student's Attendance System with Parent's Supervision is an online platform designed to help parents monitor their child's attendance in real-time. The system provides access to attendance records, alerts for low attendance, and detailed attendance statistics to promote parental involvement in academic monitoring.

## Features
- **Real-time Attendance Tracking**: Parents can view attendance records instantly.
- **Automated Alerts**: Notifications for attendance below 75%.
- **User Roles**:
  - **Admins**: Manage attendance records, users, and system settings.
  - **Teachers**: Update and review student attendance.
  - **Students**: View personal attendance reports.
- **Database Management**:
  - Implements SQL queries for CRUD operations.
  - Uses advanced database techniques like joins, triggers, and stored procedures.
- **Security & Transactions**:
  - Ensures ACID properties for data consistency.
  - Implements concurrency control mechanisms.

## System Requirements
### Hardware:
- Server with sufficient processing power to handle concurrent users.
- Workstations (PCs, laptops, or mobile devices) with an internet connection.
- Network infrastructure for stable communication.

### Software:
- **Database**: MySQL/PostgreSQL
- **Backend**: Java with JDBC for database connectivity
- **Frontend**: Java Swing for UI
- **Development Tools**: Eclipse, IntelliJ IDEA

## Database Design
- **ER Diagram**: Illustrates relationships between users, students, and attendance records.
- **Relational Schema**: Defines tables for users, students, classes, and attendance.
- **Normalization**: Applied up to **BCNF** to minimize redundancy.
- **SQL Operations**:
  - **DML Queries**: Aggregation, Joins, Views, Subqueries
  - **Triggers & Cursors**: Automate database operations

## Transaction & Concurrency Control
- **ACID Properties**:
  - **Atomicity**: Ensures complete or no transactions.
  - **Consistency**: Maintains data integrity across updates.
  - **Isolation**: Prevents conflicts in concurrent transactions.
  - **Durability**: Ensures data persistence.
- **Concurrency Control**:
  - Implements locking and timestamp-based mechanisms.
  - Supports rollback and commit operations.

## Future Enhancements
- **Cloud Integration**: Deploy the system for broader accessibility.
- **Mobile App**: Develop an Android/iOS version.
- **AI-based Analysis**: Implement predictive analytics for attendance patterns.
- **Enhanced Security**: Multi-factor authentication and encrypted transactions.

## Contributors
- **Shreyash Singh**
- **Prakeerth G**

