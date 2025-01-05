# Backend Service for Job Seeking Website

## Overview
This backend service is designed to support a job seeking website. It provides APIs for job listings, user authentication, and application management.

## Features
- User Authentication
    - Register new users
    - Login existing users
    - Password reset functionality

- Job Listings
    - Create, read, update, and delete job postings
    - Search and filter job listings

- Applications
    - Submit applications for job postings
    - Track application status

## Technologies Used
- **Programming Language:** JavaScript, 
- **Framework:** Node.js with Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **API Documentation:** Swagger

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/job-seeking-website-backend.git
    cd job-seeking-website-backend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up the environment variables:
    Create a `.env` file in the root directory and add the necessary environment variables (e.g., database connection string, JWT secret).

4. Run the development server:
    ```bash
    npm run dev
    ```

## API Endpoints

### Authentication
- `POST /api/auth/register/` - Register a new user
- `POST /api/auth/login/` - Login an existing user
- `POST /api/auth/password-reset/` - Reset password

### Job Listings
- `GET /api/jobs/` - List all job postings
- `POST /api/jobs/` - Create a new job posting
- `GET /api/jobs/{id}/` - Retrieve a specific job posting
- `PUT /api/jobs/{id}/` - Update a specific job posting
- `DELETE /api/jobs/{id}/` - Delete a specific job posting

### Applications
- `POST /api/applications/` - Submit a new application
- `GET /api/applications/{id}/` - Retrieve a specific application
- `PUT /api/applications/{id}/` - Update a specific application
- `DELETE /api/applications/{id}/` - Delete a specific application

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact [your-email@example.com](mailto:your-email@example.com).
