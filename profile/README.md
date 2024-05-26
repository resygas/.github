# resygas

![ResyGas Logo](./profile/Vector.png)

## Overview
resygas is a comprehensive system designed to enhance the reservation experience for hard-to-get restaurants. Our organization comprises three main branches, each serving a unique purpose within the system.

## Branches

### 1. resygas-api
This branch houses a FastAPI application that interacts with Resy's API and our MongoDB database. The primary responsibilities of this branch include:

- Managing and interacting with restaurant reservations.
- Handling user authentication and authorization.
- Performing CRUD operations on the MongoDB database.

### 2. resygas-tasks
This branch contains an Airflow instance responsible for automatically running scheduled tasks. Key functionalities include:

- Scheduling and automating reservation tasks.
- Managing periodic data synchronization with external APIs.
- Handling any background processing required for the API and App.

### 3. resygas-app
This branch contains a React.js web application that provides a user-friendly interface for making reservations at hard-to-get restaurants. Features include:

- Searching and browsing available reservations.
- Managing user profiles and reservation history.
- Providing real-time notifications for reservation status updates.
