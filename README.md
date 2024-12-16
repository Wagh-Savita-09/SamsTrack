Title:-SmartTrackTally

Smart TrackTally is an  Student Attendance System that simplifies attendance management. it is developed an attendence tracking system using some technologies like spring boot  for backend, hibernate ORM, mysql 8 for data storing, and postman for API testing.
It includes Layered Architecture:
1. Controller Layer:
        Responsible for handling incoming HTTP requests, processing them, and returning appropriate responses.
        Controllers act as the entry point to the application and delegate business logic to the service layer.

2. Service Layer:
    Acts as an intermediary between the controller and the data access layer (DAO).
    It contains business logic and orchestrates interactions between different parts of the application.
    Services handle tasks such as validation, data manipulation, and transaction management.

 3. DAO (Data Access Object) Layer:
     Responsible for interacting with the database and performing CRUD (Create, Read, Update, Delete) operations on the underlying data.
     DAOs abstract away the details of database interactions and provide a clean interface for the service layer to work with.

It includes key modules:
Student Module: Allows students to view and track their attendance records.
User Module: Manages different roles (students, faculty, admins) with secure login and access control.
Subject Module: Organizes attendance by subjects and courses, ensuring subject-specific tracking.
Attendance Record Module: Captures real-time attendance data, providing accurate records and reports.
Faculty Module: Enables faculty to mark attendance, view student presence, and generate attendance reports.
