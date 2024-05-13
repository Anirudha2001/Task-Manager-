# Task Manager

## Overview
This is a simple Task Management Web Application designed to help users organize and manage their tasks efficiently. The application provides a user-friendly interface for creating, updating, deleting, and viewing tasks. It consists of a backend API service built with Flask and a frontend interface developed using React.

## Features
- **RESTful API**: Backend API supports CRUD operations for managing tasks.
- **User Interface**: Responsive and intuitive frontend interface with List View, Details View, and Add/Edit View.
- **Data Persistence**: Tasks are stored in a SQLite database for persistence.
- **Authentication** (Bonus): User authentication system allows users to register, login, and logout.
- **Deployment** (Bonus): Application is deployed to Heroku for accessibility.

## Backend API
The backend API provides the following endpoints:

- `GET /tasks`: Fetch all tasks.
- `GET /tasks/:id`: Fetch a single task by ID.
- `POST /tasks`: Add a new task.
- `PUT /tasks/:id`: Update a task by ID.
- `DELETE /tasks/:id`: Delete a task by ID.

### Technologies Used:
- Java
- HTML
- CSS
- SQL

## Frontend
The frontend interface includes the following views/pages:

- **List View**: Displays all tasks with the ability to delete a task.
- **Details View**: Shows details of a single task.
- **Add/Edit View**: Form for adding a new task or editing an existing one.


## Authentication (Bonus)
A simple user authentication system is implemented, allowing users to register, login, and logout. Only logged-in users can perform CRUD operations.

### Technologies Used:
- Authentication Framework/Library: Flask-JWT-Extended

## Deployment (Bonus)
The application is deployed to Heroku for accessibility. You can access the live application [here](insert live application URL).

## Setup Instructions
1. Clone the repository: `git clone [repository URL]`
2. Install dependencies for backend and frontend.
3. Configure the database connection in the backend.
4. Run the backend server: `python app.py` inside the backend directory.
5. Run the frontend server: `npm start` inside the frontend directory.


## Functionality

![UI](https://github.com/Anirudha2001/Task-Manager-/blob/main/task%20manager/images/ui.png)

## Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for any feature requests or bug fixes.


