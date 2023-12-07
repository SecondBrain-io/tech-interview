# Exercise: Social Media API Exercise

## Objective
Design and implement a RESTful API for a social media platform. The API should facilitate user registration, posting updates, following other users, and retrieving a personalized feed. Additionally, implement user authentication to secure the API.

## Requirements
### User Model
Define a User model with the following attributes:
  * ID (auto-generated)
  * Username
  * Email
  * Password (hashed)
  * Registration Date

### Post Model
Define a Post model with the following attributes:
  * ID (auto-generated)
  * Content
  * Timestamp
  * Author (User who created the post)

### API Endpoints
Implement the following RESTful endpoints using a framework of your choice:
  * POST /users: Register a new user.
  * POST /login: Authenticate a user and generate a JWT token.
  * POST /posts: Create a new post.
  * GET /posts: Retrieve a personalized feed for the authenticated user, including posts from users they follow.
  * POST /users/follow/{username}: Allow users to follow other users.

### User Authentication
  * Implement user authentication using JWT like or user password.
  * Ensure that post-related and following-related endpoints are protected and can only be accessed by authenticated users.

### Validation and Error Handling
  * Implement proper input validation for user registration and post creation.

Handle errors gracefully and return meaningful error messages with appropriate HTTP status codes.

### Testing
Write unit tests for at least one endpoint.

Include tests for both successful and unsuccessful scenarios.

## Additional Considerations (Optional)
* Implement pagination for the list of posts to manage large datasets.
* Add the ability for users to unfollow other users.
* Implement user profile endpoints to view user details and posts.
* Use a database of your choice (e.g., PostgreSQL, MongoDB) to persist user and post data.

# Submission
Share the codebase along with a README file explaining how to set up and run the application. Include details on API usage, authentication, error handling, and any additional features implemented.

Note: Feel free to use any programming language, framework, or additional libraries that you are comfortable with. The exercise is designed to assess your skills in API design, database interaction, user authentication, and testing.
