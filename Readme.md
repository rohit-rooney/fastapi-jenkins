# FastAPI + Jenkins CI/CD Example

This is a sample project to learn **CI/CD with Jenkins** using FastAPI.

### Run Locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Run test
```bash
pytest
```

### Build and run with Docker
```bash
docker build -t fastapi_jenkins .
docker run -p 8000:8000 fastapi_jenkins
```