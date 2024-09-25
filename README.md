# Smart India Hackathon Workshop
# Date:27/08/2024
## Register Number:212223230167
## Name: RAKSHA DHARANIKA V
## Problem Title:
Development of e-Portal for Facilitating Case Management Hearing of Various Types of Cases

## Problem Description:
The project involves the development of an e-Portal for facilitating Case Management Hearings, which are referred to as "Pre-Trial Conferences" in other jurisdictions. This portal will manage case files from filing to disposal, ensuring that all related processes are streamlined and efficiently handled. The Case Management System (CMS) will keep records of all cases filed in the Delhi High Court, with features including:

Filing of Cases
Caveat Matching
Case Allocation
Daily Case Proceedings
Notice Generation
Case Transfer
Case Status Search
Report Generation
Problem Creator's Organization:
Ministry of Law and Justice


## Idea:

The idea is to create a comprehensive e-Portal that streamlines the management of case hearings, making the process more transparent, efficient, and accessible. By automating various aspects of case management, the system will reduce manual errors, save time, and improve overall case handling efficiency.

## Proposed Solution / Architecture Diagram:
Solution Overview:

User Interface: A user-friendly interface built using React.js that allows users to easily navigate and manage their cases.
Backend System: A robust backend powered by Node.js and Express.js, providing the necessary APIs and processing capabilities to handle case management operations.
Database: A NoSQL database, MongoDB, to store and manage the unstructured data related to cases, ensuring quick access and scalability.
Authentication: Secure authentication using OAuth 2.0 to protect user data and provide access control.
Real-time Communication: Implement WebSockets to enable real-time updates and communication between users and the server, such as live updates on case statuses.

## Architecture Diagram:
![image](https://github.com/user-attachments/assets/2def4cd2-414e-4575-8804-e8de33eb4357)

## Use Cases:
### Case Filling:

Users can submit case details and documents electronically.
The system matches the case with any existing caveats.
### Case Allocation:

The system automatically allocates cases to judges based on predefined criteria.
### Daily Case Proceedings:

Judges and lawyers can record and view daily proceedings, with real-time updates available to all stakeholders.
### Notice Generation:

Automatic generation and dissemination of notices to relevant parties.
### Case Status Search:

Users can search for the status of their cases using various filters.
### Report Generation:

The system can generate various reports on case statuses, progress, and other metrics.
## Use case diagram:
![Screenshot 2024-09-08 122919](https://github.com/user-attachments/assets/1dededfd-9fd2-4dfa-871e-a1aceda5de4f)

## Technology Stack:
Node.js: Runtime environment for backend development.
Express.js: Framework for building web applications and APIs.
MongoDB: NoSQL database for storing unstructured data.
React.js: Library for building user interfaces.
OAuth 2.0: Protocol for secure authentication.
WebSockets: Protocol for real-time communication between the client and server.
## Dependencies
Node.js: Ensures efficient server-side processing and handling of asynchronous operations.
Express.js: Facilitates the creation of robust web applications and APIs.
MongoDB: Provides a flexible database solution that can handle large volumes of unstructured data.
React.js: Allows for the creation of dynamic and responsive user interfaces.
OAuth 2.0: Secures user authentication and access control.
WebSockets: Enables real-time communication and updates between the server and clients.

