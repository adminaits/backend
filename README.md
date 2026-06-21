# Backend

FastAPI backend for Render.

## Local run
```bash
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
uvicorn app.main:app --reload --port 8000
```

## Render start command
```bash
uvicorn app.main:app --host 0.0.0.0 --port $PORT
```

Set all `.env.example` variables in Render Environment Variables.
