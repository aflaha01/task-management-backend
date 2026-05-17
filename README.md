# Task Management System Backend

Backend API for the Task Management System built using Django, Django REST Framework, JWT Authentication, and PostgreSQL.


## Tech Stack

- Python
- Django
- Django REST Framework
- PostgreSQL
- JWT Authentication
- Simple JWT
- django-cors-headers
- python-decouple

---

## Features

- User authentication
- JWT token-based login system
- Task CRUD operations
- PostgreSQL database integration
- RESTful API architecture
- Environment variable management
- Class-based API views
- CORS configuration for frontend integration

---

## Project Setup

### Clone Repository

```bash
git clone https://github.com/aflaha01/task-management-backend
cd backend
```

## Project Structure

```text
backend/
├── api/
├── core/
├── venv/
├── .env
├── .gitignore
└── manage.py
```

## Getting Started

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment
cp .env.example .env
# Fill in DB credentials and SECRET_KEY

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
```

## Environment Variables

```env
SECRET_KEY=your-secret-key
DEBUG=True
DB_NAME=taskflow_db
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
CORS_ALLOWED_ORIGINS=http://localhost:5173
```

**Author:** AFlaha