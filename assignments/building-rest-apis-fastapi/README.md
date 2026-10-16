# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API with FastAPI that lets clients manage tasks. Practice defining API routes, validating request data, and using HTTP methods and status codes.

## 📝 Tasks

### 🛠️ Create and Run a FastAPI Application

#### Description
Create a FastAPI application for a task-management API and start it with a development server.

#### Requirements
Completed program should:

- Create a FastAPI application in `main.py`.
- Provide a `GET /` endpoint that returns a JSON message confirming the API is running.
- Start the application with Uvicorn and make the interactive API documentation available at `/docs`.


### 🛠️ Add Task Creation and Listing

#### Description
Define the task data and implement endpoints for creating tasks and listing all tasks. Store tasks in memory; a database is not required.

#### Requirements
Completed program should:

- Define task data with an integer ID, a non-empty title, and a `completed` value that defaults to `false`.
- Implement `POST /tasks` to create a task and return it with a unique ID and HTTP status `201 Created`.
- Implement `GET /tasks` to return all created tasks as a JSON list.
- Validate incoming task data with a Pydantic model.


### 🛠️ Retrieve, Update, and Delete Tasks

#### Description
Add endpoints to operate on an individual task by its ID and return an appropriate response when a task does not exist.

#### Requirements
Completed program should:

- Implement `GET /tasks/{task_id}` to return the matching task.
- Implement `PUT /tasks/{task_id}` to update the task's title and completion status.
- Implement `DELETE /tasks/{task_id}` to remove the task.
- Return HTTP status `404 Not Found` when a requested task ID does not exist.
- Verify the endpoints and their request and response formats using the interactive `/docs` page.
