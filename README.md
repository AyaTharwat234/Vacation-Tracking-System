# Vacation Tracking Systm

## Vision 🌟
A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

## Index
1. [Requirements](#requirements)
   - [Functional Requirements](#functional-requirements)
   - [Non-Functional Requirements](#non-functional-requirements)
2. [Use Cases](#use-cases)
3. [Use Case Actors](#use-case-actors)
4. [Use Case: Manage Time](#use-case-manage-time)
5. [Database Diagram](#database-diagram)
6. [Use Case Diagram](#use-case-diagram)
7. [Flow Diagram](#flow-diagram)
8. [Sequence Diagram](#sequence-diagram)

## 1. Introduction
The Vacation Tracking System (VTS) is designed to efficiently manage employee leave requests, approvals, and time awards. This report outlines the functional and non-functional requirements necessary for the successful implementation of the VTS.

## 2. Functional Requirements
Functional requirements describe the specific behaviors and functionalities the VTS must have to meet the project's needs.

### 2.1 User Management
- The system must provide functionalities for user registration, authentication, and authorization.
- The system should support roles for different types of users, such as employees and managers.
- The system should allow users to reset their passwords and manage their profiles.

### 2.2 Leave Request Management
- Employees must be able to submit leave requests for different types of leave (e.g., vacation, sick leave, personal time off).
- The system must track and display the status of each leave request (e.g., pending, approved, denied).
- The system should provide a calendar view for employees to see their leave schedules.

### 2.3 Leave Approval Management
- Managers must be able to review and approve or deny leave requests submitted by employees.
- The system should notify managers of new leave requests via email or system notifications.
- Managers should be able to add comments or feedback when approving or denying a leave request.

### 2.4 Time Awarding
- Managers must be able to award additional leave time to employees as needed.
- The system should update the employee’s leave balance automatically upon awarding time.
- The system must notify employees of any awarded leave time via email or system notifications.

### 2.5 Leave Balance Management
- Employees must be able to view their current leave balances, including vacation, sick leave, and personal time off.
- The system should provide a detailed breakdown of leave balances, including accrued, used, and remaining leave.

### 2.6 Personal Information Management
- Employees must be able to update their personal information, such as address and contact details.
- The system should validate and save the updated information securely.
- The system must notify relevant departments of any changes to employee information.

### 2.7 Reporting and Analytics
- The system must provide reporting capabilities for both employees and managers.
- Managers should be able to generate reports on leave usage, approval times, and employee leave balances.
- Employees should be able to generate personal leave reports.

### 2.8 Notifications and Alerts
- The system should send notifications and alerts to users regarding leave requests, approvals, denials, and awarded time.
- Notifications should be configurable by users to be sent via email, SMS, or in-app notifications.

### 2.9 Integration with HR Systems
- The system must integrate with existing HR systems to synchronize employee data and leave balances.
- The system should support data import/export functionalities for easy integration with other systems.

### 2.10 Audit and Logging
- The system must maintain an audit trail of all user activities, including login attempts, leave requests, approvals, and changes to personal information.
- The system should provide logs for system administrators to monitor and review system activities.

## 3. Non-Functional Requirements
Non-functional requirements describe the system's operational attributes and constraints to ensure usability, reliability, performance, and supportability.

### Usability
- The system should have an intuitive user interface that is easy to navigate.
- User manuals and help documentation should be provided.

### Performance
- The system should respond quickly and handle many users simultaneously without slowing down.

### Reliability
- The system should be available and operational almost all the time.
- Backup and recovery procedures should prevent data loss.

### Security
- All data should be encrypted and protected.
- The system should comply with data protection regulations.
- Regular security checks should be conducted.

### Maintainability
- The system should be easy to update and modify.
- Detailed technical documentation should be provided.

### Scalability
- The system should be able to grow and handle more users as needed.
- Cloud deployment options should be considered for flexibility.

### Compatibility
- The system should work with various web browsers and devices.
- The system should integrate with existing HR systems and databases.

## 4. Constraints
- **Utilization of Current Infrastructure**: The system should utilize the existing IT infrastructure to minimize additional costs.
- **Integration with Existing Intranet Portal**: The system must integrate seamlessly with the current intranet portal.
- **Communication with Old HR Systems**: The system must be capable of communicating with legacy HR systems to ensure continuity and data integrity.
  
## 5. Use Cases

### 5.1 Use Case Diagram
- A brief description or image related to the Use Case Diagram can be added here.

### 5.2 Manage Time Use Case
This section contains detailed use cases related to managing time within the system.

#### 5.2.1 Create Request
- Employees can create a request for time off (vacation, sick leave, etc.).
- The request will be sent to their manager for approval.
  
#### 5.2.2 Withdraw Or Edit Pending Request
- Employees can withdraw or edit a request that has not yet been approved.
- Once withdrawn, the request will no longer be considered by the manager.

#### 5.2.3 Cancel Approved Request
- Employees can cancel a previously approved request if necessary.
- Cancellation will notify the manager and adjust the leave balance accordingly.

## Use Case Actors
Description of the actors involved.

## Use Case: Manage Time
Detailed description of how time is managed in the system.

## Database Diagram
![Database Diagram](https://link-to-your-image.png)

## Use Case Diagram
![Use Case Diagram](https://link-to-your-image.png)

## Flow Diagram
![Flow Diagram](https://link-to-your-image.png)

## Sequence Diagram
![Sequence Diagram](https://link-to-your-image.png)
# Project Name

## Vision 🌟
A brief description of what your project does and its purpose.

## Index
1. [Requirements](#requirements)
   - [Functional Requirements](#functional-requirements)
   - [Non-Functional Requirements](#non-functional-requirements)
2. [Use Cases](#use-cases)
3. [Use Case Actors](#use-case-actors)
4. [Use Case: Manage Time](#use-case-manage-time)
5. [Database Diagram](#database-diagram)
6. [Use Case Diagram](#use-case-diagram)
7. [Flow Diagram](#flow-diagram)
8. [Sequence Diagram](#sequence-diagram)

## Requirements

### Functional Requirements
- Requirement 1
- Requirement 2

### Non-Functional Requirements
- Requirement 1
- Requirement 2

## Use Cases
Detailed use cases.

## Use Case Actors
Description of the actors involved.

## Use Case: Manage Time
Detailed description of how time is managed in the system.

## Database Diagram
![Database Diagram](https://link-to-your-image.png)

## Use Case Diagram
![Use Case Diagram](https://link-to-your-image.png)

## Flow Diagram
![Flow Diagram]([https://github.com/AyaTharwat234/Vacation-Tracking-System/blob/main/Flowcharts/Flowchart%20%26%20Sequence%20Diagrams%20-%20Cancel%20Request.png])

## Sequence Diagram
![Sequence Diagram](https://link-to-your-image.png)
