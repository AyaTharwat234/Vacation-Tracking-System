# Vacation Tracking Systm

## Vision 🌟
A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

## INDEX
1. [Vision](#1-vision)
2. [Functional Requirements](#2-functional-requirements)
3. [Non-Functional Requirements](#3-non-functional-requirements)
4. [Constraints](#4-constraints)
5. [Use Cases](#5-use-cases)
   - [5.1 Use Case Diagram](#51-use-case-diagram)
   - [5.2 Manage Time Use Case](#52-manage-time-use-case)
     - [5.2.1 Create Request](#521-create-request)
     - [5.2.2 Withdraw Or Edit Pending Request](#522-withdraw-or-edit-pending-request)
     - [5.2.3 Cancel Approved Request](#523-cancel-approved-request)
4. [Use Case: Manage Time](#use-case-manage-time)
6. [Use Case Diagram](#use-case-diagram)
7. [Flow Diagram](#flow-diagram)
8. [Sequence Diagram](#sequence-diagram)

## 1. Introduction
The Vacation Tracking System (VTS) is designed to efficiently manage employee leave requests, approvals, and time awards. This report outlines the functional and non-functional requirements necessary for the successful implementation of the VTS.

## 2. Functional Requirements
Functional requirements describe the specific behaviors and functionalities the VTS must have to meet the project's needs.

### Functional requirements:
1. **Flexible System for Leave Requests:** The system must follow company policies and rules for validating and verifying leave time requests.
2. **Manager Approval:** It should enable manager approval of leave requests if needed.
3. **Access to Past and Future Requests:** The system must provide access to leave requests from the previous 12 months and allow requests up to 18 months in advance.
4. **Email Notifications:** The system should use email to notify managers for approval and inform employees about request status.
5. **Override Capabilities:** HR and system admins should be able to override rules, with the system keeping track of these changes.
6. **Direct Leave Awarding:** The system must allow managers to directly award personal leave time, within set limits.
7. **Web-Based UI for Internal Systems:** It should provide a web-based interface for other internal systems to review an employee's request summary.
8. **Integration with HR Systems:** The system should connect with existing HR systems to pull necessary employee information and ensure accurate leave management.

## 3. Non-Functional Requirements
Non-functional requirements describe the system's operational attributes and constraints to ensure usability, reliability, performance, and supportability.

### Non-Functional requirements:
1. **Ease of Integration and Compatibility:** The system should be complementary and easy to integrate, supporting single sign-on (SSO) mechanisms for authentication.
2. **Activity Logging:** The system must keep activity logs for all transactions.

## 4. Constraints
List any constraints here.

## 5. Use Cases
Detailed description of use cases.

### 5.1 Use Case Diagram
![Use Case Diagram](path-to-your-use-case-diagram-image.png)

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

- **Employee:** The main user of this system, managing their vacation time.
- **Manager:** An employee who has all the abilities and goals of a regular employee, but with the added responsibility of approving vacation requests for immediate subordinates. A manager may award subordinates comp time, subject to certain limits set in the system.
- **Clerk (HR Member):** A member of the HR department who has sufficient rights to view employees’ personal data and is responsible for ensuring that employees’ information in all HR systems is up to date and correct. An HR clerk can add or remove nearly any record in the system. In real life, HR clerks may or may not be employees; however, if they are employees, they use two separate login IDs to manage these two different roles.
- **System Admin:** Responsible for the smooth running of the system’s technical resources (e.g., Web server, database) and for collecting and archiving all log files.


## Use Case: Manage Time
Detailed description of how time is managed in the system.

## Database Diagram
![Database Diagram](https://link-to-your-image.png)

## Use Case Diagram
![Use Case Diagram](https://link-to-your-image.png)

## Flow Diagram
![Flow Diagram](Flowcharts/Flowchart%20-%20Managetime.png)

## Sequence Diagram
![Sequence Diagram](https://link-to-your-image.png)



