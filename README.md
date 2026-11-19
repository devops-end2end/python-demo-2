# python-demo-2

This app demonstrates the wonderousness of the Golden Path

## Requirements

- Python 3.12+
- Pip / virtual environment

## Getting Started

### 1. Set up a virtual environment

```bash
python3.12 -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

```bash
pip install --upgrade pip
pip install -e ".[dev]"
```

### 3. Run the development server

```bash
uvicorn app.main:app --reload --port 8000
```

The API will be available at:
- Service root: [http://localhost:8000](http://localhost:8000)
- Interactive Swagger docs: [http://localhost:8000/docs](http://localhost:8000/docs)
- Health check: [http://localhost:8000/api/v1/health/](http://localhost:8000/api/v1/health/)

### 4. Run tests

```bash
pytest
```