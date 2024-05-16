# NodeJS/TypeScript Coding Challenge

## Project Overview

You are required to build a REST API with CRUD functionalities for a session-based authentication system. The API will manage a data model provided in a JSON file. You will use SQLite as the database and can choose any ORM that supports SQL databases as first-class citizens. Follow REST API and backend best practices, use clean code principles and design patterns where it makes sense according to your own judgment, and maintain a modular project structure with separation of concerns and the single responsibility principle in mind. Please use Node.js with Express and TypeScript to fulfill the task.

## Requirements

### REST API with CRUD functionalities

- Implement CRUD operations for the provided data model.
- Session-based authentication using tokens.
- Provide one dummy endpoint which shall only be accessible to authenticated users that are logged in. It shall just return the string 'Authenticated!!!' and a status code of 200.

### Database

- Use SQLite as the database.
- Choose an ORM (e.g., TypeORM, Sequelize) that supports SQL databases.

### Project Structure

- Maintain a clean, modular project structure.
- Apply separation of concerns and the single responsibility principle.

### TypeScript

- Use TypeScript with explicit typing.
- Configure TypeScript according to your usual workflow in Express.

### Third-Party Packages

- You are free to use third-party npm packages of your choice within the limits of the given requirements.

### README File

- Include a short project description.
- Provide instructions on how to run the project.

## Nice to Haves

- Unit or integration tests.
- OpenAPI (Swagger) documentation for the API.

## Provided Data Model (example)

The data model is provided in a JSON file named `dataModel.json`:

```json
{
    "user": {
        "id": "number",
        "username": "string",
        "password": "string",
        "email": "string"
    },
    "session": {
        "id": "number",
        "userId": "number",
        "token": "string",
        "createdAt": "string"
    }
}
```