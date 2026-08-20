# DIVASTRA — Render deployment

Build command: `pip install -r requirements.txt`
Start command: `gunicorn app:app`
Health check: `/api/health`

Set these Environment Variables in Render:
- MYSQL_HOST
- MYSQL_PORT (usually 3306)
- MYSQL_USER
- MYSQL_PASSWORD
- MYSQL_DATABASE

The MySQL database must already contain the tables from `backend_python/schema.sql`.
Do not commit passwords or `.venv` to GitHub.
