# FastAPI-ADN

# Run this project
```
uvicorn sql_app.main:app --reload
```
# alembic migrations
```
alembic revision -m "create account table"
```
# Running our First Migration
```
alembic upgrade head
```