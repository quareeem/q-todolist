# Todo List Application

This project is a simple Todo List application. It allows users to manage their tasks efficiently, with features to add, update, delete, and view tasks.

## Features

- **Create a Task**: Add new tasks to your todo list.
- **List Tasks**: View all the tasks in your todo list.
- **Update a Task**: Mark tasks as completed or update their details.
- **Delete a Task**: Remove tasks that are no longer needed.

## Technologies

- Python 3.10
- FastAPI
- Uvicorn (for serving the application)

## Getting Started

### Prerequisites

Ensure you have Python 3.10 or later installed on your system. You can download Python from [python.org](https://www.python.org/).

### Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/todolist-fastapi.git
```

2. Navigate into the project directory:

```
cd todolist-fastapi
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

### Running the Application

Start the FastAPI server:

```
uvicorn main:app --reload
```

The application will be available at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## API Endpoints

| Method | Endpoint       | Description                |
|--------|----------------|----------------------------|
| POST   | /tasks/        | Create a new task          |
| GET    | /tasks/        | Retrieve all tasks         |
| GET    | /tasks/{id}    | Retrieve a task by its ID  |
| PUT    | /tasks/{id}    | Update a task by its ID    |
| DELETE | /tasks/{id}    | Delete a task by its ID    |
