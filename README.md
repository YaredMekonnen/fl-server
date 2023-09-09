# Fl-Server

Fl-server is a RESTful API for a recipe management application. It provides endpoints for creating, retrieving, updating, and deleting recipes. It also handles user registration, login, and authentication using secure methods.

## Features

- User Authentication: Handles user registration, login, and authentication using secure methods.
- Recipe Management: Provides endpoints for creating, retrieving, updating, and deleting recipes.
- Database Integration: Integrates with a database system to persist recipe and user data.
- RESTful API: Follows REST architectural principles for a consistent and well-structured API design.
- Error Handling: Implements error handling and validation to ensure robustness and data integrity.
- Security: Implements security measures, such as password hashing and authentication middleware, to protect user data.

## Technologies Used

- Node.js: JavaScript runtime environment for server-side development.
- Express.js: Web application framework for building APIs and handling HTTP requests.
- Postgres: Open-source relational database management system.
- Sequelize: Promise-based Node.js ORM for Postgres.
- JWT (JSON Web Tokens): Used for secure user authentication and session management.
- Bcrypt: Library for password hashing and verification.

## Prerequisites

To run the FlavorfulAPI server locally, ensure that you have the following software installed:

- Node.js: Version 14 or higher
- npm: Version 6 or higher

## Getting Started

1. Clone the repository:

   ```shell
   https://github.com/YaredMekonnen/fl-server.git
   ```

2. Install the required dependencies:

   ```shell
   npm install
   ```

3. Create a `.env` file in the root directory of the project and add the following environment variables:

   ```shell
    DB_USERNAME=your_username
    PORT = 3000
    DB_NAME = flavorful
    DB_USER = DB_USERNAME
    DB_PASSWORD = your_password
    DB_HOST = localhost
    DB_PORT = 5432
    JWT_SECRET_KEY = your_secret_key
    JWT_EXPIRES_IN = your_expiration_time
    JWT_ALGORITHM = HS256
   ```

4. Start the server:

   ```shell
   npm run dev (for development mode)
   ```
