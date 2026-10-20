# Day 9 — Full-Stack Task Manager Integration

## Objective
Connect a React frontend to a FastAPI backend and PostgreSQL database to create a working full-stack Task Manager application.

## Technologies Used
- React
- JavaScript
- Python
- FastAPI
- PostgreSQL
- REST API
- Git and GitHub

## Features
- Display all tasks
- Add new tasks
- Mark tasks as completed
- Delete tasks
- Store tasks in PostgreSQL
- Communicate between frontend and backend using REST APIs

## Application Architecture

React Frontend → FastAPI Backend → PostgreSQL Database

The frontend sends HTTP requests to the backend. The backend processes requests and reads or updates task information in PostgreSQL.

## How to Run the Application

### 1. Start the Backend

Open a PowerShell terminal and run:

```powershell
cd "C:\Users\RUPASWATHI\OneDrive\Desktop\fullstack-learning\day06-fastapi-postgresql"
.\.venv\Scripts\python.exe -m uvicorn src.main:app --reload
```

Keep this terminal running.

### 2. Start the Frontend

Open a second terminal and run:

```powershell
cd "C:\Users\RUPASWATHI\OneDrive\Desktop\fullstack-learning\day08-react-task-manager"
npm.cmd run dev
```

Open the local URL displayed by Vite, usually `http://localhost:5173/`.

### 3. Test the Application
1. Add a task.
2. Mark the task as completed.
3. Refresh the page and verify that the change persists.
4. Delete a task and verify that it disappears.

## Related Repositories
- Frontend: https://github.com/rupakola-1234/day08-react-task-manager
- Backend: https://github.com/rupakola-1234/day06-fastapi-postgresql

## Learning Outcomes
- Integrated a React frontend with a FastAPI backend.
- Used REST API requests to manage tasks.
- Connected backend operations to PostgreSQL persistence.
- Practised testing and version control with Git and GitHub.

## Project Status
Day 9 integration documentation completed. The application should be run and tested with both the frontend and backend services running.
