# FastAPI CRUD API

A fast, clean, and robust RESTful CRUD API built using **FastAPI**, **SQLAlchemy** (SQLite database), and **Pydantic**.

Inspired by live API demonstrations on Render ([fastapi-crud-api-8ilh.onrender.com](https://fastapi-crud-api-8ilh.onrender.com)).

## Features

- **Full CRUD Support**: Create, Read (List & Single), Update, and Delete items.
- **Data Validation & Serialization**: Managed seamlessly using Pydantic schemas.
- **ORM Integration**: Powered by SQLAlchemy with SQLite.
- **Auto Documentation**: Built-in interactive OpenAPI / Swagger UI documentation (`/docs`).

## Project Structure

```text
fastapi_crud/
├── main.py          # FastAPI app entrypoint & routing
├── models.py        # SQLAlchemy database models
├── schemas.py       # Pydantic validation & response schemas
├── crud.py          # Database helper functions
├── database.py      # Database engine & session setup
├── requirements.txt # Python dependencies
└── README.md        # Documentation
```

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Suyash990/fastapi-crud-api.git
cd fastapi-crud-api
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the application
```bash
python -m uvicorn main:app --reload
```

Open your browser and navigate to:
- **Welcome Endpoint**: `http://127.0.0.1:8000/`
- **Interactive Swagger UI**: `http://127.0.0.1:8000/docs`
