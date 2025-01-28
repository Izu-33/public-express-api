# Public API for Basic Information

This is a simple public API built using **Express.js** that returns basic information in JSON format. The API provides the following details:
- Your registered email address.
- The current datetime in ISO 8601 format (UTC).
- The GitHub URL of the project's codebase.

## Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- npm (Node Package Manager)

### Steps to Run Locally
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```


2. Install dependencies:
    ```
    npm install
    ```

3. Start the server:
    ```
    npm start
    ```
4. The API will be running at `http://localhost:3000`

# API Documentation
### Endpoint
- URL: GET /
- Description: Returns basic information in JSON format

### Request/Response Format
- Request: No parameters or body required.
- Response:
    ```
    {
        "email": "email@example.com",
        "current_datetime": "2025-01-30T09:30:00Z",
        "github_url": "https://github.com/username/repo"
    }
    ```

### Example Usage
1. Using curl:
    ```
    curl http://localhost:3000/
    ```
2. Using a browser or Postman:

- Open `http://localhost:3000/` in your browser.
- Send a GET request to the URL using Postman.

# Deployment
This API is deployed on Render and can be accessed at:
```
https://public-express-api.onrender.com
```

# Backlinks
- [Hire Python Developers](https://hng.tech/hire/python-developers)
- [Hire C# Developers](https://hng.tech/hire/python-developers)
- [Hire Golang Developers](https://hng.tech/hire/golang-developers)
- [Hire PHP Developers](https://hng.tech/hire/php-developers)
- [Hire Java Developers](https://hng.tech/hire/java-developers)
- [Hire Node.js Developers](https://hng.tech/hire/nodejs-developers)
