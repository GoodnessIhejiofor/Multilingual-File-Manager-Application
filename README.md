# Multilingual-File-Manager-Application

# Project Overview

This project will allow you to showcase your backend development skills learned throughout the course. It integrates essential concepts like databases, i18n, queuing systems, and unit testing in a practical application.

# Project Description:

Develop a multi-user file manager application using Node.js, Redis, and MySQL. The application should:

1. User Management: Allow user registration and login with secure password storage.
2. File Management: CRUD operations on files (create, read, update, delete) within a user's designated directory structure.
3. Multilingual Support (i18n): Display user interface elements (labels, messages) in different languages based on user preferences.
4. Queuing System: Implement a queue using Redis to handle asynchronous tasks like file uploads or conversions (optional: add progress tracking).
5. Unit Testing: Write unit tests for core functionalities, covering user registration, file management operations, and possibly the queuing system.
   
# Technical Considerations:
1. Databases:
  MySQL: Store user data, file metadata (name, size, type etc.) and directory structure.
  Redis: Implement a queue for asynchronous tasks. Consider libraries like Bull or Agenda.js
2. Node.js Framework: Encourage using a lightweight framework like Express.js to structure the application.
3. Authentication: Use a secure hashing algorithm (e.g., bcrypt) for password storage. Consider libraries like Passport.js for user authentication.
4. i18n Libraries: Explore libraries like i18next for managing and implementing multilingual functionalities.
5. Testing Framework: Use a popular testing framework like Jest or Mocha for unit testing


# Project Deliverables:

1. Functional Backend Application: A working Node.js application demonstrating the outlined functionalities.
2. Source Code: Well-organized and commented codebase.
3. Unit Tests: A suite of unit tests covering core functionalities.
4. Project Documentation: A brief document outlining the project setup, technical choices, and usage instructions.
