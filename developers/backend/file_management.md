# Exercise: File Storage Service Exercise

## Objective
Design and implement a file storage service that allows users to upload, download, and delete files. Additionally, implement user authentication and access control to secure the service.

## Requirements
1. File Model
  * Define a File model with the following attributes:
    * ID (auto-generated)
    * Name
    * Size
    * Upload Date
    * Owner (User who uploaded the file)
2. API Endpoints
  * Implement the following RESTful endpoints using a framework of your choice:
    * POST /files: Upload a new file.
    * GET /files: Retrieve a list of all files.
    * GET /files/{id}: Download a specific file by ID.
    * DELETE /files/{id}: Delete a specific file.
3. User Authentication
  * Implement user authentication using JWT.
    * Create endpoints for user registration and login.
    * Ensure that file-related endpoints are protected and can only be accessed by authenticated users.
4. Access Control
  * Implement access control to restrict file access based on ownership.
  * A user should only be able to download or delete files they uploaded.
5. Validation and Error Handling
  * Implement proper input validation for file uploads.

Handle errors gracefully and return meaningful error messages with appropriate HTTP status codes.

6. Testing
* Write unit tests for at least one endpoint.
* Include tests for both successful and unsuccessful scenarios.

## Additional Considerations (Optional)
* Implement file type validation to allow only specific file formats.
* Add pagination for the list of files to manage large datasets.
* Implement logging to track file uploads, downloads, and deletions.
* Use a database of your choice (e.g., MongoDB, MySQL) to persist file and user data.

## Submission
Share the codebase along with a README file explaining how to set up and run the application. Include details on API usage, authentication, access control, and any additional features implemented.

Note: Feel free to use any programming language, framework, or additional libraries that you are comfortable with. The exercise is designed to assess your skills in API design, database interaction, user authentication, access control, and testing.


