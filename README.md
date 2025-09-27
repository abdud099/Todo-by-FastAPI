# Todo-by-FastAPI

A simple **Todo application** built with **FastAPI** and managed with **Poetry**.
This project demonstrates a clean API design, dependency management, and easy setup for Python developers.

---

## Features

- CRUD operations for Todos
- FastAPI-powered REST API
- Easy dependency management using Poetry
- Automatic API docs with Swagger UI and ReDoc
- Lightweight and fast

---

## Requirements

- Python 3.10+
- Poetry (for dependency management)

---

## Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/todo-by-fastapi.git
cd todo-by-fastapi
```

2. **Install dependencies using Poetry**

```bash
poetry install
```

3. **Activate virtual environment**

```bash
poetry shell
```

4. **Run the FastAPI application**

```bash
uvicorn main:app --reload
```

- The app will run at: `http://127.0.0.1:8000`
- API docs: `http://127.0.0.1:8000/docs`
- ReDoc: `http://127.0.0.1:8000/redoc`

---

## Project Structure

```
todo-by-fastapi/
├── main.py          # FastAPI app entry point
├── models.py        # Database models
├── schemas.py       # Pydantic schemas
├── crud.py          # CRUD operations
├── poetry.lock      # Poetry lock file
├── pyproject.toml   # Poetry configuration
└── README.md        # Project documentation
```

---

## Usage

- Create a todo
- Read all todos
- Update a todo
- Delete a todo

---

## Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin feature-name`
5. Open a Pull Request

---

## License

MIT License © [Your Name]