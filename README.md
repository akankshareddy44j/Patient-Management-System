Patient-Management-System
A full-stack application designed to manage patient data, appointments, prescriptions, and billing in a healthcare domain. It integrates with third-party health services and provides secure, role-based authentication for doctors, patients, and admins.

Tech Stack
Frontend: Angular
Backend: .NET Core
Database: SQL Server
ORM: Entity Framework
Containerization: Docker
CI/CD: Azure DevOps

Features
Role-based Authentication: Secure access for Doctors, Patients, and Admins.
Patient Management: Add, edit, and delete patient records, including personal details and medical history.
Appointments: Schedule and track appointments for patients with doctors.
Prescriptions: Create and manage prescriptions for patients.
Billing: Track billing information for patient services.
Third-party API Integration: Securely integrates with external health service APIs.

Installation
1. Clone the repository:
   git clone https://github.com/your-username/Patient-Management-System.git
   

2. Navigate to the project directory:
   cd Patient-Management-System

3. Set up the backend:
   Ensure that you have .NET Core and SQL Server installed.
   Update connection strings and other necessary configurations in the `appsettings.json`.

4. Set up the frontend:
   Navigate to the Angular app directory:
     cd frontend
Install required dependencies:
     npm install

5. Docker: Build and run the app with Docker:
   docker-compose up --build

6. CI/CD Setup: The project is integrated with Azure DevOps for continuous integration and deployment.

How to Contribute
Feel free to fork the repository, submit issues, and pull requests for improvements. If you're contributing code, please ensure that it adheres to the existing coding standards and includes tests where applicable.
