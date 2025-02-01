# Kanban Board with JWT Authentication

This project is a Kanban board application with JWT authentication. Users can securely log in and access the board using JSON Web Tokens (JWT) for authentication.

# Features

-Secure login page with username and password.

-JWT-based authentication for user login.

-Protected routes to ensure users are authenticated before accessing the Kanban board.

-JWT stored securely in local storage for authenticated requests.

-Session expiration after a defined period of inactivity.

![Kanban Board1](https://static.bc-edx.com/coding/software-dev/14-Full-Stack-React/assets/14-00-unauthenticated-page.png)
![Kanban Board2](https://static.bc-edx.com/coding/software-dev/14-Full-Stack-React/assets/14-01-login-page.png)
![Kanban Board3](https://static.bc-edx.com/coding/software-dev/14-Full-Stack-React/assets/14-02-main-page.png)

## Getting Started:

1. Clone the repository:
```
git clone <repository-url>

cd <project-directory>
```
2. Create a .env file with the following environment variables:
```
DATABASE_USERNAME=<your-database-username>

DATABASE_PASSWORD=<your-database-password>

JWT_SECRET_KEY=<your-secret-key>
```
3. Complete the authentication setup:

-Implement JWT authentication in ```server/src/middleware/auth.ts.```

-Implement login functionality in ```server/src/routes/auth-routes.ts.```

-Add authentication to API routes in ```server/src/routes/index.ts.```

-Complete client-side authentication in ```client/src/api/authAPI.tsx``` and ```client/src/utils/auth.ts.```

-Deploy the app to Render using the Render Deployment Guide and PostgreSQL Guide.

4. Deploy the app to Render:

Follow the Render Deployment Guide for deploying the app.

5. Use Insomnia for testing the API directly.


## Tech Stack:

-Frontend: React, JSX, CSS

-Backend: Node.js, Express.js, JWT, PostgreSQL

-Authentication: JSON Web Tokens (JWT)

-Deployment: Render

## Deployment:

The application is deployed and access it here: 

## Contributing:

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. 

## License:

This project is licensed under the MIT License.

