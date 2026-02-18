# College Management System (Microservices Architecture)

A robust, scalable management system designed to handle educational workflows, including student services, faculty management, and course coordination. Built with a focus on modular design and high data integrity.

Key Features:
* **Microservices Design:** Decoupled services (Student, Faculty, Course) managed via **Netflix Eureka Service Discovery**.
* **Full-Stack Integration:** Dynamic front-end interacting with backend services via RESTful APIs.
* **Database Management:** Relational data handling ensuring 100% functional accuracy for student and faculty records.
* **Secure Feedback System:** Dedicated module for faculty evaluations and feedback processing.

Tech Stack:
* **Frontend:** JavaScript, HTML5, CSS3
* **Backend:** Java (Spring Boot logic), Python
* **Infrastructure:** Eureka Server for Service Discovery
* **Database:** SQL / MySQL

System Architecture:
The system follows a microservices pattern where each core module operates independently:
1. **Eureka-Server:** The central registry for service discovery.
2. **Student-Service:** Handles enrollment, profiles, and academic records.
3. **Faculty-Service:** Manages staff data and department assignments.
4. **Course-Service:** Facilitates course registration and scheduling.

Testing & Quality Assurance:
* **Unit Testing:** Verified core service logic to ensure modular reliability.
* **Integration Testing:** Validated end-to-end communication between the frontend and microservices.
* **Documentation:** Comprehensive technical specifications for each API endpoint.

How to Run:
1. Clone the repository: `git clone https://github.com/sreevamsee/CollegeManagementSystem.git`
2. Start the `eureka-server` first.
3. Launch individual services (`Student-Service`, `Faculty-Service`, etc.).
4. Open the `front-end` directory and launch the application.


