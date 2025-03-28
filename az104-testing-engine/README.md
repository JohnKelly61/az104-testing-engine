# AZ-104 Testing Engine

A web-based testing engine to help prepare for the Microsoft AZ-104 exam. Built with FastAPI (Python) and React.

## Features
- Upload PDFs to extract questions
- Manually preload questions by category
- Randomized quiz generation
- Timer and scoring
- Review incorrect answers with explanations
- Export results

## Tech Stack
- FastAPI (backend)
- React (frontend)
- SQLite (database)
- Docker (containerized deployment)
- PyMuPDF (PDF parsing)

## Getting Started

### Prerequisites
- Docker
- Git

### Clone the repository

```bash
git clone https://github.com/Johnkelly61/az104-testing-engine.git
cd az104-testing-engine
```

### Run with Docker

```bash
docker-compose up --build
```

The backend will be available at `http://localhost:8000`  
The frontend will be available at `http://localhost:3000`

## Folder Structure

- `backend/` - FastAPI app
- `frontend/` - React app
- `database/` - SQLite DB storage

## License
MIT

## Author
[Johnkelly61](https://github.com/Johnkelly61)
