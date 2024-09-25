
**Project Title:** Vehicle Management System

**Objective:**
Develop a backend service for managing vehicle data that integrates with a global authorization provider (gAuth). The service should be scalable, secure, and deployable on a cloud platform using Kubernetes.

**Requirements:**
- Implement the backend service using Go (Golang).
- Design and implement RESTful APIs for managing vehicle data.
- Integrate the service with a mock global authorization provider (gAuth).
- Ensure the solution is cloud-agnostic and can be deployed on any major cloud provider (AWS, Google Cloud, Azure).
- Use Docker and Kubernetes for containerization and orchestration.
- Implement automated tests for the APIs.
- Document the project, including setup, deployment instructions, and API documentation.

**Tasks:**

1. **Project Setup:**
   - Create a new GitHub repository for the project.
   - Set up a Go project with necessary dependencies.
   - Initialize Docker and Kubernetes configurations.

2. **API Development:**
   - Design and implement RESTful APIs for the following operations:
     - Create a new vehicle record.
     - Retrieve vehicle information by ID.
     - Update vehicle information.
     - Delete a vehicle record.
     - List all vehicles.
   - Ensure proper validation and error handling for all endpoints.

3. **gAuth Integration:**
   - Implement a mock gAuth service to simulate the integration.
   - Secure the APIs using token-based authentication (OAuth 2.0).
   - Ensure that each API request is authenticated and authorized using gAuth tokens.

4. **Database Management:**
   - Choose a suitable database (SQL or NoSQL) for storing vehicle data.
   - Implement database models and data access layers.
   - Optimize database queries for performance.

5. **Containerization and Orchestration:**
   - Write Dockerfile(s) to containerize the application.
   - Create Kubernetes deployment and service files for the application.
   - Ensure the application can be deployed on a cloud provider's Kubernetes service (e.g., AKS, GKE, EKS).

6. **Testing:**
   - Write unit and integration tests for the APIs.
   - Set up a CI/CD pipeline using GitHub Actions to run tests and deploy the application to a Kubernetes cluster.

7. **Documentation:**
   - Create a README file with project description, setup instructions, and usage guide.
   - Document the API endpoints using tools like Swagger or Postman.
   - Provide detailed deployment instructions for deploying the application on a cloud provider.

8. **Code Review and Submission:**
   - Push the code to the GitHub repository.
   - Ensure the repository is public or share access with the reviewer.
   - Submit the GitHub repository link along with any necessary credentials for accessing the deployed application.

**Evaluation Criteria:**
- **Code Quality:** Clean, readable, and well-documented code.
- **API Design:** Efficient and scalable API design with proper validation and error handling.
- **Security:** Proper implementation of authentication and authorization.
- **Cloud Deployment:** Successful deployment on a cloud provider using Kubernetes.
- **Testing:** Comprehensive unit and integration tests.
- **Documentation:** Clear and thorough project and API documentation.

---

**Submission Instructions:**
1. Fork the repository and create a branch named `develop`.
2. Complete the project as per the requirements.
3. Push the code to your GitHub repository.
4. Create a pull request to merge your `develop` branch into the `main` branch.
5. Submit the pull request link along with any relevant deployment credentials to **[your email/contact]**.

**Project Deadline:**
- The project must be completed and the pull request submitted by [deadline date].
