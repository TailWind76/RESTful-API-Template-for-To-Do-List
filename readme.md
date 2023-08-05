
# RESTful API Template for To-Do List

This is a simple RESTful API template built using Node.js, Express.js, and MongoDB with Mongoose. The API allows you to manage tasks for a To-Do List.

## Getting Started

To get started with this API template, follow the steps below:

1. **Prerequisites**: Make sure you have Node.js and MongoDB installed on your system.

2. **Clone the repository**: Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/todo-api-template.git
   ```

3. **Install dependencies**: Navigate to the project directory and install the required dependencies:

   ```
   cd todo-api-template
   npm install
   ```

4. **Configure MongoDB**: Before running the API, make sure you have MongoDB running locally or provide the correct MongoDB connection URL in `index.js`.

5. **Run the server**: Start the server by running the following command:

   ```
   node index.js
   ```

   The server will run on `http://localhost:3000` by default.

6. **API Endpoints**: The following API endpoints are available:

   - **POST /api/task**: Create a new task. Use JSON body with fields `title` and `description`.

   - **GET /api/task**: Get all tasks.

   - **GET /api/task/:id**: Get task by ID. Replace `:id` with the task ID.

   - **PUT /api/task/:id**: Update task by ID. Replace `:id` with the task ID. Use JSON body with fields `title` and `description` to update.

   - **DELETE /api/task/:id**: Delete task by ID. Replace `:id` with the task ID.

## Data Model

The task data model includes the following fields:

- `title`: The title of the task (required).
- `description`: The description of the task.
- `completed`: The completion status of the task (default: false).
- `createdAt`: The timestamp of task creation (auto-generated).

## Contributions

Feel free to fork this repository and adapt it to your specific needs. Contributions and suggestions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

