# Java-Backend-Microservices-JobMS

Job Microservice

Overview
The Job Microservice manages job listings within my platform, providing functionalities to create, update, retrieve, and delete job postings. It plays a crucial role in connecting job seekers with opportunities offered by companies on my platform.
#
Features
Job CRUD Operations: Create, read, update, and delete operations for managing job postings.
Job Listings: Store and retrieve details such as job title, description, company ID, location, min salary and max salary.
Integration: Seamlessly integrates with other microservices, such as Company and Review microservices, to provide comprehensive job-related functionalities.
#
Dependencies
Database: Utilizes PostgreSQL database for storing job data.
Docker: Postgres docker container used for database.
#
Endpoints
GET /jobs: Retrieve a list of all job postings.
GET /jobs/{jobId}: Retrieve details of a specific job posting by ID.
POST /jobs: Create a new job posting.
PUT /jobs/{jobId}: Update an existing job posting.
DELETE /jobs/{jobId}: Delete a job posting by ID.
#
Error Handling
Proper HTTP status codes and error messages are returned for different scenarios (e.g., 404 for not found, 401 for unauthorized access).
